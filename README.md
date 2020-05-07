# Displaying distance data from an ultrasonic sensor onto a LCD with the Raspberry Pi 4.
A project that periodically displays the distance data from an ultrasonic sensor to a LCD as "Dist: 0.00cm." 
For GPIO pin mapping, I used WiringPi (Made by Gordon Henderson under GNU-LGPL) to simplify. Link: http://wiringpi.com/

***WiringPi Note: The author has discontinued public releases of WiringPi. The last update was 2.52 for the Raspberry Pi 4B.***

Hardware components used:
- (1) HC-SR04 Ultrasonic Sensor
- (1) I2C LCD1602 Module
- (8) Male to Female Jumper Cables
- (1) Breadboard
- Raspberry Pi 4B Rev. 1.2

When compiling the code, run the following commands in terminal at the location of the file:
```
sudo bash
gcc UltrasonicSensorInfoOnLCD.c -o UltrasonicSensorInfoOnLCD -lwiringPi -lwiringPiDev
./UltrasonicSensorInfoOnLCD
```
This project was possible through an electronics kit I purchased from Freenove that provided me with all of the components I used. 
If interested, it is the "Freenove Ultrasonic Starter Kit for Raspberry Pi" (FNK0024).
