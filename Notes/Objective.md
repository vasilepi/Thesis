## Main Goals
1. The robot should be able to locate victims
	1. Should have a camera and flashlights
2. The robot should be able to transport medical and other supplies to the victims
	1. Should have a storage box
3. The robot should be able to maneuver through the collapsed terrain
	1. Should have tracks
	2. Should have track flippers ([reference](https://www.researchgate.net/profile/Manop-Wongsaisuwan/publication/224441658_Plasma-RX_Autonomous_Rescue_robots/links/00b7d52267a813ab72000000/Plasma-RX-Autonomous-Rescue-robots.pdf))
    
		![image](https://github.com/user-attachments/assets/7e453098-29f4-4430-a01a-48af13ae01a0)
4. The robot should be compact and fast enough
	1. Following the guidelines of the Robocup Robot Rescue Competition (2005) the robot should be no bigger than $$70\times70\times70 \ cm^3$$
5. The robot should be able to traverse the terrain without facing easy derailment
	1. Should have a close-to-the-ground COG and big inertia values along the critical rotation axes (**X, Y**)
		![image](https://github.com/user-attachments/assets/d02f7677-2755-45df-a3bc-ee0dfb2a667e)
	2. (Should have mechanisms to return to original state if it flips)
6. The robot should be lightweight (cost efficient)
7. The robot's autonomy should be high
	1. Large battery life

## Requirements
- The robot should be less than $80\times 80 \times 80 \ cm^3$ (total)
- The robot should weigh less than $40\ kg$ (total weight)
- The robot must implement configurable flipper tracks
- The robot's average battery life should be at least 1 day
- The robot should have a safety factor of 2 for all the components except critical components where the safety factor should be 3
- The robot must implement a storage box that can carry up to $5\ kg$ medical/food/rescue supplies. In more detail the storage should be no greater than $20\times 18\times 10\ cm^3$


## Pass/Fail Criteria
These criteria are for the FEA later on:
Fails if the $MoS\le1$ 


## Time Plan
![image](https://github.com/user-attachments/assets/c54281eb-5d3e-416a-9ac8-e0669fdab438)

![image](https://github.com/user-attachments/assets/76b0c0f8-2033-4a1d-8297-286e516ed34a)



