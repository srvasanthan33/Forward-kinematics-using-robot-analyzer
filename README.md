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
![image](https://github.com/srvasanthan33/Forward-kinematics-using-robot-analyzer/assets/102546622/ca7ad229-4ff8-47d9-92f2-73a1236c36bd)







### SIMULATION 
 ![image](https://github.com/srvasanthan33/Forward-kinematics-using-robot-analyzer/assets/102546622/2b6142af-4575-4610-bcd4-158c44ff709a)


 
 ### PLOT 
 **Links**
  Link 1:
  ![image](https://github.com/srvasanthan33/Forward-kinematics-using-robot-analyzer/assets/102546622/39d8df4c-be4e-4579-95b8-df6d1b4d8519)
Link2 :
![image](https://github.com/srvasanthan33/Forward-kinematics-using-robot-analyzer/assets/102546622/2f44d08d-ec0a-44ce-ba30-a38731055332)

Link 3:
![image](https://github.com/srvasanthan33/Forward-kinematics-using-robot-analyzer/assets/102546622/d789f01c-02ad-4603-b009-4834225f4e14)
Link 4:
![image](https://github.com/srvasanthan33/Forward-kinematics-using-robot-analyzer/assets/102546622/317669de-110f-4e0f-b7a7-f50830f7e14b)
Link 5 :
![image](https://github.com/srvasanthan33/Forward-kinematics-using-robot-analyzer/assets/102546622/92128923-d643-4990-8f1a-dc5be0c95375)

Link 6 :
![image](https://github.com/srvasanthan33/Forward-kinematics-using-robot-analyzer/assets/102546622/ae98ca9c-5153-48fe-9acf-31e9aea2d45a)



**Joints**

Joint 1 :
![image](https://github.com/srvasanthan33/Forward-kinematics-using-robot-analyzer/assets/102546622/52307390-0196-4a6e-8751-7a4976e1d77f)

Joint 2:
![image](https://github.com/srvasanthan33/Forward-kinematics-using-robot-analyzer/assets/102546622/7bf754f0-1f9d-4b6a-bea0-8e269adfd439)

Joint 3:
![image](https://github.com/srvasanthan33/Forward-kinematics-using-robot-analyzer/assets/102546622/bb5c3e37-4643-49fb-971b-d9564b1b2ddb)

Joint 4:
![image](https://github.com/srvasanthan33/Forward-kinematics-using-robot-analyzer/assets/102546622/4a4290e2-6f14-4f5d-be43-3e97604df909)

Joint 5:
![image](https://github.com/srvasanthan33/Forward-kinematics-using-robot-analyzer/assets/102546622/7898b9cd-9dba-415d-a78c-b4979f6c6a1c)

Joint 6:
![image](https://github.com/srvasanthan33/Forward-kinematics-using-robot-analyzer/assets/102546622/cbd9e2a2-f883-4a01-b7d9-7dd3e057151e)


### RESULTS :  

The forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer and polt the graph for link cordinates and joint angles has been analysed
