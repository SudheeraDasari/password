# SPEED AND DIRECTION CONTROL OF DC MOTOR USING ARDUINO

## ABSTRACT

 DC Motor direction control by using Arduino is the main title of the project. By using this Arduino we can see how tO control DC Motor and we can control the direction of dc motor by simply controlling the input voltage to the motor by using potentiometer.We here use L293D chip motor driver as H-bridge.The main purpose of using L293D chip is that it can control speed and direction of dc motor.To complete this task we have to do programming in Arduino. 

## INTRODUCTION

DC Motors are found everywhere: electronics, toys, fans, tools, discs, pumps etc. DC Motor is an actuator that converts the DC supply to rotation or movement.There are different types of DC motors: Brushed DC motor, Brushless DC motor, Geared DC motor, Servo motor, Stepper motor and DC Linear Actuator.Different types of motors are used in different applications like Robotics, precision positioning, industrial automation etcGenerally, when a DC motor is associated with any microcontroller based system, it is often connected using a Motor Driver IC. A Motor Driver IC provides the necessary current for the motor to run. It can also control the direction of the rotation.
In this project, an Arduino based speed and direction control of DC motor with using Motor Driver IC is designed. 

## LITERATURE SURVEY

Our project main part called Arduino UNO is very important, it is open source circuit used in every electronic project work. Electronic device are become more compact, flexible and inexpensive.The DC motor is an attractive piece of equipment in many industrial applications requiring variable speed applications due to its ease of controllability. Speed of dc motor varies proportionally to the input voltage.With the fixed suplly voltage the speed of the motor can be changed by switching the supply on and off so frequently that the motor notices only the average voltage effect and not the switching operation. 

## High Level Requirements

* To rotate in clockwise direction
* To rotate in anti-clock wise direction.
* To control the speed of the motor using potentiometer.
* To develop the simulation  of control unit.
* To test and validate the designed system.

## Low Level Requirement

* By varying the value of potentiometer the speed should be varied.
* Push button is provided to rotate in clockwise direction.
* push button is provided to rotate in anti-clockwise direction.

## S.W.O.T Analysis

![image](https://user-images.githubusercontent.com/87614111/155712022-4b22d919-09df-451d-b3fc-5bac8dcf3e5d.png)

# Strengths
 * Speed can be controlled very easily.
 * We can instantly change the direction of motor.
 
# Weaknesses
* If over voltage arise it is chance to damage the motor.
* It can not work beyond its barrier
* Noisy operstion because of dc motor.

# Oppurnities
 * The scope of this system is more at industries and where there is variable speed of motors are required.

# Threats
* High initial cost for hardware design.
* Maintainence cost increases.

## 4W's And 1H

# Who
The Speed control of dc motor  are used in industries,domestic,robotic applications.

# What
Speed control of dc motor is used to control the spped and direction of dc motor intantly.

# When
Speed control of dc motor is used when the motor needs to change its direction and speed according to the requriment.

# Where
These are used in industrial,domestic,robotics,defences,communication applications.

# How
 The circuit uses a potentiometer to change the speed and Arduino is used interfaced with potentiometer to sense the change of potentiometer which changes speed.The direction is changed by using the push buttons for clock and anti-clock wise directions.
 
 # Applications
 * Robotic application – to change direction and speed of moving robot
 * Industrial application – to change direction and speed of rotating machinery
 * Domestic application – to vary speed of battery (DC) operated portable fan
 * Defence application – to rotate radar, automatic gun, tank gun in either direction
 * Communication application – rotate dish antenna upward – downward or clockwise – anticlockwise.

## BLOCK DIAGRAM



![bd](https://user-images.githubusercontent.com/87614111/156154175-5b79d394-e55c-4bd4-8314-35eddb9c8630.jpg)



## Potentiometer:

Light sensor is used to sense amount of light. There are many light sensors available in market but Light dependent resistor (LDR) is used as a light sensor. Because it is cheap in price, easily available in market and can be easily interfaced with microcontroller to sense intensity of light. LDR have property to change its resistance according to intensity of light. If light is high, LDR will have low resistance and if light is low, LDR will have high resistance. So microcontroller can easily read this resistance in the form of voltage and which can be back converted into proportional value of light. In this I am using push buttons gor light sensor.

# ACTUATOR

## DC motor
  DC Motor has part of many equipment and machinery. We are using 6v DC motor, It is device that can use in industrial equipment as small device and it also chipper and used in robotics, Quadcopter, and internet of the things project. DC motor work on the current and voltage needed for the capabilities of microcontroller but DC moto necessary to use some external device of electronic to drive the and control the motor and it required individual power supply. There are many ways to drive the DC motor from their output of device. however, transistor also use full to drive the DC motor and the other way to control the direction of the motor is L298 drive it is integrated circuit.

## Arduino Uno

 It is a Microcontroller Based prototyping board. The microcontroller used on the Arduino Uno board is ATmega328p. Arduino is responsible for controlling the speed and direction of the motor with the help of other components.It has 14 digital input/output pins,6 analog inputs,a 16MHz quartz crystal,a USB connection, apower jack,an ICSP header and a reset button.The circuit uses a potentiometer to change the speed and Arduino is used interfaced with potentiometer to sense the change of potentiometer which changes speed.It has come with wide range of application. Number of people are using Arduino board for developing instrument and project for scientific research. Here some application

1)Security and defense system
2)Digital electronics and robotics
3)Traffic light count down timer
4)Medical instrument
5)Parking lot counter

## POWER SUPPLY
It is used for supplying the circuit.

## Push Buttons
In this project we are using two push buttons which are connected to arduino. This are used to change the directiuon of motor either in clockwise or anti-clock wise direction as per needed.

## L293D chip
 This chip takes input from Arduino uno and drives DC motor. The Arduino output current is not enough to drive DC motor directly. The chip has quad half H bridge drivers. It will provide up to 600 mA current to motor that is enough to drive it.

 

## Flow Chart

![speed](https://user-images.githubusercontent.com/87614111/156151960-3cc90b9b-283c-46bc-a8ea-d91e3a331fb0.jpg)
