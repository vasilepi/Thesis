## Main Goals
1. The robot should be able to locate victims
	1. Should have a camera and flashlights
2. The robot should be able to transport medical and other supplies to the victims
	1. Should have a storage box
3. The robot should be able to maneuver through the collapsed terrain
	1. Should have tracks
	2. Should have track flippers ([reference](file:///C:/Users/Vasilis/Downloads/Plasma-RX19.pdf))
		![[Pasted image 20241025153248.png|300]]
4. The robot should be compact and fast enough
	1. Following the guidelines of the Robocup Robot Rescue Competition (2005) the robot should be no bigger than $$70\times70\times70\;cm^3$$
5. The robot should be able to traverse the terrain without facing easy derailment
	1. Should have a close-to-the-ground COG and big inertia values along the critical rotation axes (**X, Y**)
		![[Pasted image 20241025152421.png|500]]
	2. (Should have mechanisms to return to original state if it flips)
6. The robot should be lightweight (cost efficient)
7. The robot's autonomy should be high
	1. Large battery life

## Requirements
- The robot should be less than $80\times 80 \times 80 \; cm^3$ (total)
- The robot should weigh less than $40\;kg$ (total weight)
- The robot must implement configurable flipper tracks
- The robot's average battery life should be at least 1 day
- The robot should have a safety factor of 2 for all the components except critical components where the safety factor should be 3
- The robot must implement a storage box that can carry up to $5\; kg$ medical/food/rescue supplies. In more detail the storage should be no greater than $20\times 18\times 10\; cm^3$


## Pass/Fail Criteria
These criteria are for the FEA later on:
Fails if the $MoS\le1$ 


## Time Plan
Put the gantt file [here](https://www.onlinegantt.com/#/gantt)

