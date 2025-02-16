### Introduction:

In this project, I calculated the required torque for each joint in a robot arm. The purpose of these calculations is to determine the torque that the servo motor must generate at each joint to effectively move the arm. Torque is the force that causes rotation of a body around a specific point or axis, and it depends on the applied force and the distance between the point where the force is applied and the axis around which the body rotates.

### Calculating Torque for Each Joint:

To calculate the torque, I used the simple torque equation:

Where:
Torque = Force×Distance

- *Force* is the weight hanging (1 kg) multiplied by the gravitational acceleration (9.81 m/s²).
- *Distance* is the distance from the joint to the center of the load.

### 1-Calculating Torque for Each Joint:

# Joint 1 (Closest to the base):

#Force:  
   F = 1 × 9.81 = 9.81 N
  
#Distance (from the base to the last joint):
   
   D = 15 + 10 + 4 = 29cm =0.29m
- Torque:  
  T_1  = 9.81 × 0.29 = 2.84 Nm = 28.4 kg.cm

#### Joint 2 (Middle):
#Force:  
  F = 1 × 9.81 = 9.81 N
- Distance (from the second joint to the end of the arm):  
D = 10 + 4 = 14cm =0.14m
- Torque:  
   T_2  = 9.81 × 0.14 = 1.37 Nm= 13.7 kg.cm

####Joint 3 (Last): :
-Force:  
  
 F = 1 × 9.81 = 9.81 N
  
- Distance (from the third joint to the end of the arm)::  

  D = 4cm=0.04m
  
- Torque:  
 
  T_3 = 9.81 × 0.04 = 0.39 Nm = 3.9 kg.cm


### 2-Choosing Servo Motors:

•Joint 1: Requires a motor with a torque of 30+ kg.cm.
Servo: Hitec.
 [Hitec 32625S HS-625MG Hi-Speed Metal Gear 2BB Servo]
(https://amzn.eu/d/blKRq51)
  
•Joint 2: Requires a motor with a torque of 15+ kg.cm.
Servo: Deegoo-FPV.
[Deegoo-FPV [4-Pack] MG996R 55g Metal Gear Torque Digital Servo Motor for Futaba JR RC Helicopter Car Boat Robot]
(https://amzn.eu/d/0XSz1ze)  

•Joint 3: Requires a motor with a torque of 5+ kg.cm.
Servo: Futaba.
[Futaba servo S3177SV 00107136-3]
(https://amzn.eu/d/1TJZELd)  

