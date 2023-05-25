Forward-kinematics-using-robo-analyzer
AIM:

To analyze the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer and polt the graph for link cordinates and joint angles.

COMPONENTS REQUIRED:

1.Robo analyzer software

THEORY:

Forward Kinematics

A manipulator is composed of serial links which are affixed to each other revolute or prismatic joints from the base frame through the endeffector. Calculating the position and orientation of the endeffector in terms of the joint variables is called as forward kinematics. In order to have forward kinematics for a robot mechanism in a systematic manner, one should use a suitable kinematics model. Denavit-Hartenberg method that uses four parameters is the most common method for describing the robot kinematics. These parameters ai1, α −,1idi and θ the link length, link twist, link offset and joint angle, respectively. A coordinate frame is attached to each joint to determine DH parameters. Zi axis of the coordinate frame is pointing along the rotary or sliding direction general manipulator.

Denavit Hartenberg Parameters With DH Parameters, solving for the Forward Kinematics is easy. only need to take four parameters for each joint i: θifor the joint angle, αi for the link twist, difor the link offset, and ai for the link length. Once I’ve obtained them, I can just plug them in to this transformation matrix:



![image](https://github.com/SUJITH04/Forward-kinematics-using-robot-analyzer/assets/130206202/a8c351ce-e771-4fbf-8655-a79c9bfc1d7b)



![image](https://github.com/SUJITH04/Forward-kinematics-using-robot-analyzer/assets/130206202/55e324cf-619a-402a-bc97-b35f64e666d9)

PROCEDURE:
```
    1.open the roboanalyzer software.
    2.select the robot and its degrees of freedom.
    3.change the values with the link lenght wherever necessary.
    4.simulate the model for forward kinematics.
    5.plot the graph between the link and the joints.
    6.update the DH parameters of the link configuration and end effector configuration.
  ```

DH PARAMETERS:

6 DOF

![image](https://github.com/SUJITH04/Forward-kinematics-using-robot-analyzer/assets/130206202/a1b81f1f-6e45-4a2b-88f3-7abe059daaf1)

4 DOF

![image](https://github.com/SUJITH04/Forward-kinematics-using-robot-analyzer/assets/130206202/ca33807b-971e-4f01-9dc1-2bb3db058d2a)

SIMULATION

6 DOF
![image](https://github.com/SUJITH04/Forward-kinematics-using-robot-analyzer/assets/130206202/aa6aeb38-61c5-43e0-afbe-5c3f9d8b6e9a)

4 DOF

![image](https://github.com/SUJITH04/Forward-kinematics-using-robot-analyzer/assets/130206202/0f958052-9329-4c3c-b30e-3bde6c900fad)

PLOT
6 DOF

![image](https://github.com/SUJITH04/Forward-kinematics-using-robot-analyzer/assets/130206202/6ddf084c-f78b-42ca-b303-f1cbaedafb6f)

4 DOF

![image](https://github.com/SUJITH04/Forward-kinematics-using-robot-analyzer/assets/130206202/f84f79fd-2101-4b86-bb42-b46da80d5575)

EE CONFIGURATION:

6 DOF

![image](https://github.com/SUJITH04/Forward-kinematics-using-robot-analyzer/assets/130206202/da5ad18c-4897-4532-ae85-e20bb7fae2ca)

4 DOF

![image](https://github.com/SUJITH04/Forward-kinematics-using-robot-analyzer/assets/130206202/b4ac8d8d-db33-45ef-bcfd-f77dd03e5bf9)

RESULTS :

Thus, the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer is analysed and the graph for link cordinates and joint angles is plotted.










