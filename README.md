# Inverse-kinematic-modeling-using-robo-analyzer-

 
## AIM: 
To analyze the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer and polt the graph of joint angle for a given  input end effector position .


### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
### Inverse Kinematics
 

Inverse kinematics is the use of kinematic equations to determine the motion of a robot to reach a desired position. For example, to perform automated bin picking, a robotic arm used in a manufacturing line needs precise motion from an initial position to a desired position between bins and manufacturing machines. The grasping end of a robot arm is designated as the end-effector. The robot configuration is a list of joint positions that are within the position limits of the robot model and do not violate any constraints the robot has.

 Most industrial robots are constructed of several independently controllable articulated joints. Each joint is connected to one or more of the other joints, sometimes in complex configurations. The end effector is attached at the end of the entire “kinematic chain”. When you move any one joint, this will affect the end effector’s pose in various ways.

This means that there is no simple, direct relationship between the end effector position and any one particular joint.

For example, if you want the robot’s end effector to move 1 mm linearly along the Z-axis, you may need to move all of the joints by a different amount.

Finally, inverse kinematics algorithms calculate the exact position of each of the robot’s joints required to reach your desired end effector pose.

### solving inverse kinematic model 
![image](https://user-images.githubusercontent.com/36288975/170622829-3fe97ef7-8ef1-44af-afae-b0954871aa0c.png)


![image](https://user-images.githubusercontent.com/36288975/170622902-f48fd9c7-f2ec-4fd5-904b-ea51be8298c3.png)

![image](https://user-images.githubusercontent.com/36288975/170622934-a3fd7f77-7eb2-4408-b66d-d6e3adbd1f99.png)

![image](https://user-images.githubusercontent.com/36288975/170622982-9c4d8b23-1563-4e17-9616-87bcc4f4501d.png)
![image](https://user-images.githubusercontent.com/36288975/170623020-f27efc12-bb58-4f62-840d-af544ac6689e.png)

### PROCEDURE:

```
NAME:KATHIRVEL.A
REG NO:212221230047
```




```
1.open the roboanalyzer software.
2.select the robot and its degrees of freedom.
3.change the values of X and Y wherever necessary.
4.simulate the model for inverse kinematics.
5.plot the graph between the joints.
6.update the DH parameters of the link configuration and end effector configuration.
```





### SIMULATION 
 
 RPR ROBOT:
 
 ![image](https://github.com/KathirvelAIDS/Inverse-kinematic-modeling-using-robo-analyzer-/assets/94911373/7753bea6-e8c8-4972-bceb-865b61852822)

 ![image](https://github.com/KathirvelAIDS/Inverse-kinematic-modeling-using-robo-analyzer-/assets/94911373/47bc3cdf-b88c-4681-b28b-c9d0b99a2796)
 
 
 
 3R ROBOT:


![image](https://github.com/KathirvelAIDS/Inverse-kinematic-modeling-using-robo-analyzer-/assets/94911373/196b4bd7-4866-4a41-a4ac-78a40cd494b6)


![image](https://github.com/KathirvelAIDS/Inverse-kinematic-modeling-using-robo-analyzer-/assets/94911373/d8c59846-0da9-41cf-b47c-12d6d1a8e1fe)

 
 
 ### PLOT 
 
 
 RPR ROBOT:
 
 
 ![image](https://github.com/KathirvelAIDS/Inverse-kinematic-modeling-using-robo-analyzer-/assets/94911373/b1d775eb-3288-470e-a565-980e3425d150)

 
 ![image](https://github.com/KathirvelAIDS/Inverse-kinematic-modeling-using-robo-analyzer-/assets/94911373/0ad54a25-d223-436d-8595-427382a84b26)

 
 
 
 3R ROBOT:

 
 
![image](https://github.com/KathirvelAIDS/Inverse-kinematic-modeling-using-robo-analyzer-/assets/94911373/7113da76-2bdd-44e8-bb26-101249b868c8)



![image](https://github.com/KathirvelAIDS/Inverse-kinematic-modeling-using-robo-analyzer-/assets/94911373/82dc8679-5faf-4b79-9a54-0ab60779865d)











### RESULTS :  


Thus,the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer is analysed and the graph of joint angle for a given input end effector position is plotted.


