# Forward-kinematics-using-robo-analyzer

## AIM: 
To analyze the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer and polt the graph for link cordinates and joint angles
### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
Forward Kinematics

A manipulator is composed of serial links which are affixed to each other revolute or prismatic joints from the base frame through the endeffector. 
Calculating the position and orientation of the endeffector in terms of the joint variables is called as forward kinematics. 
In order to have forward kinematics for a robot mechanism in a systematic manner, one should use a suitable kinematics model. 
Denavit-Hartenberg method that uses four parameters is the most common method for describing the robot kinematics. 
These parameters ai1, α −,1idi and θ the link length, link twist, link offset and joint angle, respectively. 
A coordinate frame is attached to each joint to determine DH parameters. Zi axis of the coordinate frame is pointing along the rotary or sliding direction general manipulator.

Denavit Hartenberg Parameters
With DH Parameters, solving for the Forward Kinematics is easy.  only need to take four parameters for each joint 
i: θifor the joint angle, 
αi for the link twist, 
difor the link offset, and 
ai for the link length. Once I’ve obtained them, I can just plug them in to this transformation matrix:


![image](https://user-images.githubusercontent.com/36288975/170172719-ed7befc9-2894-4344-bfd5-be831bb05308.png)

 ![image](https://user-images.githubusercontent.com/36288975/170172766-b8aeb788-7fd7-4de7-b340-f04656707ebd.png)

 

### PROCEDURE:

1. Open Robo Analyzer application 
![image](https://github.com/srvasanthan33/Forward-kinematics-using-robot-analyzer/assets/102546622/a80c1021-a5ed-416a-9cbc-d5b4febf2a28)
2. Change DOF to 6
![image](https://github.com/srvasanthan33/Forward-kinematics-using-robot-analyzer/assets/102546622/f9f84a07-a6cc-4b74-a84b-bd1aef80ad95)
3. Set Parameters
![image](https://github.com/srvasanthan33/Forward-kinematics-using-robot-analyzer/assets/102546622/125c0588-ef80-40da-8d90-b37298ce1822)
4. Click Fkin to simulate
![image](https://github.com/srvasanthan33/Forward-kinematics-using-robot-analyzer/assets/102546622/d1b49fe4-30f3-4362-a8f5-02b152e5981a)
5. Plot the graphs







### SIMULATION 
 

 
 ### PLOT 
  
 

 
 
 
 
 
 
 
 
 
 

 
 














### RESULTS :  
