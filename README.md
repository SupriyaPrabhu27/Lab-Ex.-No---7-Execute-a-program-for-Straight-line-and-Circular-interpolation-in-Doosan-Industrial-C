## 212224240165
## SUPRIYA PRABHU


# Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-cobot
## Aim : To Execute a program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio.

## Components Required:

*Doosan Industrial Collaborative Robot

*DRL (Doosan Robotics Language) Studio Software

### Theory 
INTERPOLATION

Interpolation, which is necessary for any type of programming, consists of generating data points between given coordinate axis positions. Within the Machine Control Unit (MCU), a device called an interpolator causes the drives to move simultaneously from the start to the end of the command. The interpolator is either an electronic hardware device for a NC system, or a software program for a CNC system. An interpolator provides two functions:

It calculates individual axis velocities to drive the tool along the programmed path at the given feed rate.

It generates thousands of intermediate coordinate points along the programmed path between the start point and the end point of the cut.

During positioning, all programmed axes move simultaneously at the specified feed rates until each axis has reached its destination. All drives start together, but without an interpolator individual destinations are reached successively according to the path traveled. However, an interpolator coordinates these axis motions in such a way that the programmed path is constantly maintained from the beginning to the end of the movement.

Linear and circular interpolation are most commonly used in CNC programming applications:

Linear interpolation is used for straight-line machining between two points.

Circular interpolation is used for circles and arcs.

Helical interpolation, used for threads and helical forms, is available on many CNC machines.

Parabolic and cubic interpolation are used by industries that manufacture parts having complex shape such as aerospace parts, and...

## Procedure:

Manipulate the end effector as per the given configuration. Movement Should Initiate in P1 and progress till the end point. Travel path should be in sequence as stated below.

Linear Interpolation








Circular Interpolation

### output

![image](https://github.com/user-attachments/assets/9a413f94-cc5d-4480-a960-2fd174cb44e5)

![image](https://github.com/user-attachments/assets/93731111-6ce1-485c-888d-68677d709fde)


![image](https://github.com/user-attachments/assets/e54f41ec-17a3-4a23-bf2d-709353cd236a)

![image](https://github.com/user-attachments/assets/e63005f7-b496-458b-9c91-f35d9fde85bf)

![image](https://github.com/user-attachments/assets/034fe8e3-9636-4f12-b2e3-eec1691e9259)

# Linear Interpolation

![image](https://github.com/user-attachments/assets/704a72c6-6aa2-4a6d-b9a2-11286f8ec282)

## Circular Interpolation

![image](https://github.com/user-attachments/assets/82628fd3-e864-47c1-a9e3-1cb4a25543f5)











### Results 

A program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio has been executed successfully.

 
