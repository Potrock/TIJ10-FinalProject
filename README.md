# TIJ10-FinalProject Group 9 Patrick, Michael, Ben
RobotC Code for Tech Design Final Project Robot X9

All functions defined at the beginning of the program; findLight spins the robot until it has found the light, and then moves towards the light until it is a certain distance away (Done using the values from the light sensor), findLight then brings the arm down to the position where it can be inside the ring, and then the function ends.


#returnMiddle
This is the function to bring the robot back to the middle, with the ring. Brings the robot back, lifts up the arm, and the function ends.

#task main
This is section that runs all the functions, and starts automatically once the robot turns on. It is structured so that:
1. Task starts, variable i is set to 0.
2. findLight is called.
3. Once findLight is complete, returnMiddle is called.
4. The 1 is added to the value of i.
5. This repeats until i = 4, meaning the robot has picked up 4 rings.

Comments beside the code also show you what is going on step by step.
