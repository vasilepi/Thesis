### SUBCASE 1
- Preliminary Design
	- Goals
	- Theoretical Geometrical Design
	- Functionalities
- Conceptual Design
	- Declare Analyses Types To Be Tested On
	- FEA to Redesign
	- Redesign to FEA
	- ...
	- Conclude On Geometry (Design Freeze)
- AIV (Whole or for a Subsystem)
	- 3D Print 1:1 Prototype
	- Detailed Assembly Procedures
	- Verification

### SUBCASE 2
- Preliminary Design
	- Goals
	- Functionalities
- Conceptual Design
	- Declare Analyses Types To Be Tested On
	- Design Freeze 1
	- FEA to Redesign
	- Redesign to FEA
	- ...
	- Conclude On Geometry (Design Freeze 2)
	- Hardware Design (Mechatronics)
		- Declare Electronics
		- PCB Design
		- Software (Part or Whole)
- Prototype
	- 3D Print a smaller scaled Prototype
	- Test/Finalize Software (on Arduino)


### SUBCASE 3
- Preliminary Design
	- Goals
	- Functionalities
- Conceptual Design
	- Declare Analyses Types To Be Tested On
	- Pass/Fail Criteria
	- Design Freeze 1
	- FEA to Redesign
	- Redesign to FEA
	- ...
	- Conclude On Geometry (Design Freeze 2)
	- Hardware Design (Mechatronics)
		- Declare Electronics
		- PCB Design
		- Software (Part or Whole)
- Prototype
	- 3D Print a smaller scaled Prototype
	- Test/Finalize Software (on Arduino)
	- AIV (for Subsystems)
		- 1:1 Scale prototypes
		- Non-detailed Assembly procedures



### Final: Mix...(TBD)
#### Rescue Robot Seeker/Medical Supplies Transporter
- Compact
- Fast
- Movement Flexibility
- Carry Supplies (Medical, Water, Food etc)
	- Implement Storage box
	- (Implement robotic arm)?
- Seek and Find survivors
	- Implement Camera
	- Implement flashlights
	- Implement Microphones/Speakers
- Maneuverability Expertise
	- Implement Sensors
	- Implement Configurable tracks
   
	![image](https://github.com/user-attachments/assets/0a32c83b-94a8-4fea-9932-a6067d3eb4fa)

	![image](https://github.com/user-attachments/assets/545b8981-ca23-4600-892a-8fd769d8510d)
	- Implement mechanisms to help when robot is unable to move (turns up-side-down, flip sideways)


### Workload
1. Introduction [[Introduction]]
	1. Rescue missions
	2. How do robots help in rescue missions
3. Objective [[Objective]]
	1. Main goals
	2. Requirements 
	3. Pass/Fail Criteria
	4. Time Plan
4. Conceptual Design
	1. Sensors and sensor location/Control systems design
	2. Mechanisms definition
	3. Weight budget
	4. Energy budget
		1. Motors for hill climb
		2. (Motors for robotic arm)
		3. Motors for miscellaneous mechanisms
	5. Revisit weight budget after motor selection
5. Preliminary Design
	1. First Geometry Iteration (CAD)
		1. `While pass/fail criteria are not met`
			1. `Calculate subparts (gears, bolt connections, bearings, shafts)`
			2. `Fix Geometry`
			3. `break`
	2. Final Geometry Iteration (CAD)
		1. Inertia Matrix
		2. COG
	3. FE Model 
	4. Structural Analysis
		1. Scenarios 
			1. Subparts analyses (tbd)
				1. MoS calculation
       					 $$MoS = \frac{Stress\ Limit}{Stress\ Applied \cdot SF} - 1$$
			2. Road Excitation - Transient (road profile tbd)
		2. Improvements based on analysis results
	5. Conclude on design
6. Prototyping
	1. Scaled Model
		1. Printable size
		2. Geometry/Mechanisms simplification 
	2. Test software for manual remote control
		1. Microcontroller Dev Board
		2. DC Motors



# TOC (tbd)

