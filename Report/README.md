# PASSWORD BASED DOOR LOCKING SYSTEM USING ARDUINO

## ABSTRACT

In this digitally dependent world, the security is most concern for every one of us. As we all are facing the fearof robbery, people cannot keep their valuable things
safely even at their own houses, banks or in any otherplaces. They are always in fear of losing their valuablethings. Old traditional locking system is not that safe password  based door locking system.So, in this project we have work for all these problem and this project provide much more lock security ascompare to traditional lock security. We have replacedthe old traditional lock system with password. Thisproject will provide efficient security to the users at lowcost. It will be also easy to implement and give safety in any places like our houses, institutions, banks or anyother public places. If the users forgot the password,then he/she will change or reset the password, which
gives the more flexibility to the users.
 

## INTRODUCTION

As we all are very familiar with the term “Security”.Nowadays it is most important to keep our valuablethings safe. The world is also growing digitallydependent, and we can even design the doors to be moresecure. We can make these digital doors by using “Password” which is more secure than traditional lock system.In this project we have make a “Password Based DoorLocking System” using an Arduino. It will be more efficient for the peoples in the field of security. It will be implemented in any places like our Houses, Institutions,Banks and any Public Places. We can only be able open the door if we entered correct password for door and if users entered an incorrect password, then message will be display or door will not be open.  

## LITERATURE SURVEY

The main objective of this project is to relinquish safety at each common place like home, public places. During this project all the data hold on within the info. once the
proper word are going to be entered, the microcontroller can provide steering to servo engine then door can unlock. What we want is computerised innovation to develop a coordinated and every one around altered upbeat framework at a worth that is wise.


## High Level Requirements

* System shall control opening of Doors by pressing a number on Keypad.
* There shall be a LCD to display the numbers we press as '*'.
* A password shall be provided for our system.

## Low Level Requirement

* According to the values of Keypad opening of door  shall be controlled.
* Entered value on keypad shall be displayed on LCD Screen as '*'.
* If the password is wrong the LCD displays as wrong password.
* Doors  shall open when the Password is matched.

## S.W.O.T Analysis

![image](https://user-images.githubusercontent.com/87614111/155712022-4b22d919-09df-451d-b3fc-5bac8dcf3e5d.png)

# Strengths
 * Less human interactions.
 * Displays password as '*' so that no one can see except that person.
 
# Weaknesses
* Some times Code hacking may possible if someone could guess our password.
* This system cannot run if there is electric problems.

# Oppurnities
 * The scope of this system is more at  home, public places etc.

# Threats
* High chances of pin hacking.
* Forgotting password can also causes risk to the users.

## 4W's And 1H

# Who
The password control door locking  are used in homes,public places.

# What
The password control door lockingr is used to provide lock for door by using password.

# When
The password control door locking is used when homes and public places needslocks for the door.

# Where
These are used in  homes and public placess.

# How
 The circuit uses a Arduino with lcd display and servo motor as a door locking.
 
 # Applications
 * This system can be used in Door Control of Houses.
 * This system can be used in Door Control of Industries.
 * This system can be used in Door Control of Stadiums etc...
 * 
## BLOCK DIAGRAM

![poasswordbased](https://user-images.githubusercontent.com/87614111/156913304-2c153a7d-5473-4811-bf7a-d4f188471a68.jpg)




## Sensor
#  4x4 Matrix Keypad
  The 4x4 Matrix Keypad interfaced is to take the input from the person. We can enter the preset password to test the validity of the password. If the password is valid then,     the door lock will be unlocked. If invalid, the door lock will continue to be locked. The 4x4 Matrix Keypad includes 4 rows and 4 columns. There is a transfer that connects     every row and column. In our project We will use only the numeric between 0-9 keys along with * to change the password.

# ACTUATOR

## LCD Display:

    Displays each and every value we enter in our keypad.

 ## Servo Motor:
 
   Helps in opening and closing our doors.

## Arduino Uno

This microcontroller depends on the ATmega328P. There are all out of 20 pins (0-19) out of which 6 are simple information sources, 14 are computerized input yield pins(6 pins give PWM voltage) which can like be utilized as broadly useful pins, a ceramic resonator of recurrence 16 MHz, a USB association, a force jack and a reset button. It has a working voltage of 5V. It contains all that expected to help a microcontroller.

 

## Flow Chart

![flowchart password](https://user-images.githubusercontent.com/87614111/156913649-8bd922e8-886f-4718-8f5d-d51765ba4567.jpg)

## TEST PLAN AND OUTPUT
High Level Test Plan
 
  |    ID	   |  Description	    | Expected I/P	  |   Expected O/P      |	 Actual O/P	   |  Type of Test  |
  |----------|------------------|-----------------|---------------------|----------------|----------------|
  |          |                  |                 |                     |                |                |
  |  HP01    |controlling of doors by pressing number on keypad   |  pressing password  |   **** |      Pass	     |  Requirement   |
  | HP02 | Lcd displays    |	  password |  matches	   |  Pass	       |  Requirement    |
  | HP03 | Incoorect password     |	   |  Opens results	   |  Pass	       |  Requirement    |
  


Low Level Test Plan
   
  | ID	 |     Description	            |  Expected I/P |	Expected O/P`	     |  Actual O/P   |	Type of Test |
  |------|----------------------------- |---------------|--------------------|---------------|---------------|
  | LP01 |  user view all the rules of the game      | 	Character y	|  starts the game   |	Pass	       |  Requirement  |
  | LP02 |  user has an option to exit	  |   Character N	|   Exits	           |  Pass	       |  Requirement  |
  | LP03 | user can view the score     |	  Character y |  Opens results	   |  Pass	       |  Requirement    |
  

