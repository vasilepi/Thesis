### Victim Identification
#### Sensors
- Camera x1
- CO2 Sensor x4 on each side (Place CO₂ sensors where airflow is likely to carry exhaled CO₂, such as ventilation pathways or enclosed areas where CO₂ from trapped individuals may concentrate.)
- Acoustic Sensor x2 Microphone bidirectional and x1 Vibe sensors (as close to the ground as possible - filtering regular vehicle vibrations out)
##### Utilization
- Camera -> Thermal with wide FOV ($> 80^ \circ$)
	- Will be used for mapping and victim identification through NN algorithms and temperature levels detection
- CO2 Sensor
	- Will be used to detect elevated CO2 levels (indication of respiration)
- Acoustic Sensor -> microphone arrays and vibration sensors
	- Detect tapping, shouts, or breathing sounds. Should have filters to remove background noise

###### Limitations
- Temperature, humidity, and ventilation can impact CO₂ readings. High humidity or dusty environments can sometimes interfere with the sensor’s readings if not calibrated to compensate for these conditions.
- CO2 sensors usually detect data within 1-2 meters close to the sensor. limits the victim location identification
- jitter from motors and robot parts can not be predicted 100% so the filtering won't totally exclude the noise from vibrations. this makes it hard for the sensor to identify victims


### Localization and Mapping

#### Sensors
- LIDAR
- IMU

##### Utilization
- Lidar -> 2D with 360 deg FOV
	- 2D environment mapping
	- Needs thermal shielding with techniques like passive cooling
		- Add layers on casing
			- fiberglass for insulation
			- aluminum foil to deflect radiant heat
			- ventilated aluminum case
- IMU 
	- To provide data:
		- acceleration from accelerometers
		- position from gyroscopes
		- direction from magnetometers

###### Limitations
- cant detect z-axis obstacle geometry




### Obstacle negotiation

#### Sensors
- LIDAR
- Camera
- IMU

##### Utilization
- Lidar
	- detect obstacle height
	- needs to be at a reasonable height from the ground
- IMU 
	- yaw, roll, pitch of robot to detect slope angles
	- measure grav forces  to detect slope angles
- Camera
	- lets the user perceive the environment better when using manual control
	- when using autonomous driving
		- If the slope is obstructed (e.g., by debris or uneven terrain), the thermal camera helps differentiate obstacles from the slope itself.
		- Variations in temperature patterns may indicate elevation changes or terrain features (e.g., debris piles or ramps).


###### Limitations
- without a second PSD or lidar sensor the base of the obstacle can not be detected/can only detect slope angle after already negotiated with the slope (in auto) -> add psd at bot of robot
- it is difficult when in autonomous driving mode to separate slopes from far away obstacles
	<img src = "https://github.com/user-attachments/assets/48f1495b-6a22-4f5e-aab7-251d31c99c63" width = 600 height=400>





