# MobileRobot-Openloopcontrol
## Aim:

To develop a python control code to move the mobilerobot along the predefined path.

## Equipments Required:
1. RoboMaster EP core
2. Python 3.7

## Procedure:

## Step1:
Start

<br/>

## Step2:
From robo master import robot.

<br/>

## Step3:
Instalaize the type.

<br/>

## Step4:
Run the program to move the robo master through our conditions.

<br/>

## Step5:
Stop.

<br/>

## Program:
Name:A.Ruchitha Reddy

Ref.no:21005032
```python
from robomaster import robot
import time

if name == 'main':
    ep_robot = robot.Robot()
    ep_robot.initialize(conn_type="ap")

    ep_chassis = ep_robot.chassis
    ep_led = ep_robot.led

    ep_led.set_led(comp="all",r=255,g=0,b=0,effect="on")   
       
    ep_chassis.move(x=2, y=0, z=0, xy_speed=1.25).wait_for_completed()
    ep_led.set_led(comp="all",r=0,g=255,b=0,effect="on") 

    ep_chassis.move(x=0, y=0, z=360, xy_speed=1.25).wait_for_completed()
    ep_led.set_led(comp="all",r=0,g=0,b=255,effect="on")  
    ep_chassis.move(x=2.5, y=0, z=0, xy_speed=1.25).wait_for_completed()
    ep_led.set_led(comp="all",r=255,g=0,b=0,effect="on") 
    ep_chassis.move(x=0, y=0, z=90, xy_speed=1).wait_for_completed() 
    ep_led.set_led(comp="all",r=0,g=255,b=0,effect="on") 

    ep_chassis.move(x=1.5, y=0, z=0, xy_speed=1.25).wait_for_completed()
    ep_led.set_led(comp="all",r=255,g=0,b=0,effect="on")
    ep_chassis.move(x=0, y=0, z=90, xy_speed=1).wait_for_completed() 
    ep_led.set_led(comp="all",r=0,g=0,b=255,effect="on")

    ep_chassis.move(x=2.5, y=0, z=0, xy_speed=1.25).wait_for_completed()
    ep_led.set_led(comp="all",r=0,g=0,b=255,effect="on")
    ep_chassis.move(x=0, y=0, z=90, xy_speed=1).wait_for_completed()
    ep_led.set_led(comp="all",r=0,g=255,b=0,effect="on")
    ep_chassis.move(x=2, y=0, z=0, xy_speed=1.25).wait_for_completed()
    ep_robot.close()
```

## MobileRobot Movement Image:
![output](https://github.com/RuchithaReddy28/mobilerobot-openloopcontrol/blob/main/mb1.jpeg?raw=true)
![output](https://github.com/RuchithaReddy28/mobilerobot-openloopcontrol/blob/main/mb2.jpeg?raw=true)

<br/>
<br/>
<br/>
<br/>

## MobileRobot Movement Video:

Upload your video in Youtube and paste your video-id here.
(https://drive.google.com/file/d/1umhyLR-6WqwYVfY7a3U_U_XWiiQR71aN/view?usp=drivesdk)


<br/>
<br/>
<br/>
<br/>

## Result:
Thus the python program code is developed to move the mobilerobot in the predefined path.


<br/>
<br/>

```
Mobile Robotics Laboratory
Department of Artificial Intelligence and Data Science/ Machine Learning
Saveetha Engineering College
```
