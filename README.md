# DeskHub - Emotionally intelligent Desktop companion robot
![Final product](images/Final-image.png)

DeskHub is a small, expressive desktop companion that responds to your interactions, shows emotions on its OLED face, 
and features a slick 3D-printed body that adds a professional finish to its charming personality.

## Features
3D-Printed Casing <br>
Emotion System - DeskHub reacts with happiness, tiredness, or excitement based on how you interact. <br>
OLED Expressions - Displays animated faces that shift with mood or environment. <br>

# Components
## Electronics
ESP32S3 – The main brain of the robot. <br>
4x DFRobot Micro Servo Motors – These handle leg movements to create an expressive, animated walk. <br>
MPU6050 Motion Sensor – Gives the robot the ability to detect orientation and movement, making interactions more dynamic. <br>
0.96" OLED Display – Used to show a wide range of animated eyes and emotions, giving DeskHub a personality. <br>
3.7V Lithium-ion Battery – Keeps DeskHub powered while staying compact and rechargeable. <br>

![Wiring schematic](images/connection.jpg)
### PCB schematic
![PCB schematic](images/PCB_schematic.jpg)

## Enclosure
Designing a compact and modular shell that can house all electronics <br>
Creating cutouts for the OLED display, servo wires, and switches <br>
Ensuring the structure was lightweight enough not to strain the servos <br>

![3D CAD](images/CAD_3dView.jpg)
### Fusion Design
#### Body
![Fusion Body](images/fusion_body_stl.jpg)
#### Cap
![Fusion Cap](images/fusion_cap_stl.jpg)
#### Legs
![Fusion Leg](images/fusion_leg_stl.jpg)

## 3D printing
![3D print](images/enclosure_mfg.jpg)
