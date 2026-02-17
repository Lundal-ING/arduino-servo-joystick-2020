# arduino-servo-joystick-2020
Arduino-based servo control using joystick ( High school project, 23.09.2020 Data Elektronikk) 

This Project was completed in September 2020 during my second year in high scool ( Data Electronics/ Data Elektronikk).
It demonstrates early hands-on experience with microcontrollers, analog inputs, and PWM control. 
Although this project is simple, its a fun and great project for new users trying to learn how to use Arduino, this was my second time doing a project with the UNO and its a bit different then only using LED's. 

# Objective 
Control two Servo motors using a joystick module connected to an Arduino Uno. 

#Hardware
- Arduino Uno
- 2x Servo motors
- Joystick module (VRX, VRY)
- Breadboard
- Jumper wires

# System Architecture

Joystick outputs two analog signals: 
- VRX -> A0 (controls Servo 1)
- VRY -> A1 (controls Servo 2)

Servos: 
- Servo 1 -> Digital pin 3 (PWM)
- Servo 2 -> Ditial Pin 5 (PWM)

Power: 
- 5V -> Breadboard power rail
- GND -> Breadboard ground rail

