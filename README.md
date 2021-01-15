# Mitsubishi Robotic Arm
This respository illustrates the project of programming a Mitsubishi RV-2A robotic arm, while utilizing components of an integrated robotic station to package certain components together into a final 1-piece component. The project was divided into four parts. In the first part, a flow chart is made and presented to have a general idea of the robotic arm functionality and sequence. After that, the XYZ coordinates that the robotic arm should reach during its task operation are taught using the teach-pendant and are uploaded to the computer. A program is written afterwards using a software that is provided with the robot (CIROS STUDIO) in the desired sequence in an itirative manner to reach the desired coordinates as accurately as possible. Lastly, the results are shown and discussed while presenting the sources of difficulties and errors that came up during the process of programing the arm.

  ![alt text](https://github.com/waliddib095/Mitsubishi-Robotic-Arm-/blob/main/Images/Screen%20Shot%202021-01-15%20at%205.12.42%20AM.png)
# Perfromed Functions

1. Moving forearm to desired XYZ coordinate, where the containers resides.
2. Using the robot gripper to hold the container and moving arm to packaging point.
3. Place container in packaging point when the IR sensor detects placement area.
4. Moving forearm to desired XYZ coordinate, where the container's cap resides.
5. Moving back to packaging area and rotating the gripper for 90 degrees to screw the cap when sensor detects the container.
6. Moving the assembeled part to delivery station.

  
# Logic Flow
![alt text](https://github.com/waliddib095/Mitsubishi-Robotic-Arm-/blob/main/Images/Screen%20Shot%202021-01-15%20at%205.16.07%20AM.png)
