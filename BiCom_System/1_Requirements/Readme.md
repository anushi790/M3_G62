## About
BiCom System is the extension of the unidirectional RKE to a bidirectional system which is a smart entry system which is an electronic lock that control access to a vehicle without using a traditional mechanical key. It doesn't rely on a physical button or panel in order to get into your vehicle, instead it has a sensor that detects your remote keyless key within range of vehicle.

## Features
- Window status of the car will be printed when Button is pressed ONCE.
- Alarm status the car will be printed when Button is pressed TWICE.
- Car battery info will be printed when the Button is pressed THRICE. 
- Door status of the car will be printed when the Button is pressed FOUR times.

## 4 W's and 1-H
| WHO | WHAT | WHEN | WHERE | HOW |
| ------------- | ------------- | ----| ----- | ----- |
| Users who want to use to print(Window status, Alarm status, Car battery info, Door status) remotely| Remote Bi-directional Key for car |When user want to use to print(Window status, Alarm status, Car battery info, Door status) remotely | Inside/Outside of the car| By applying no of pushes on button for that feature| 

## SWOT Analysis
| STRENGTHS | WEAKNESSES | OPPORTUNITIES | THREATS |
| ------------- | ------------- | ----| ----- |
| No Mechanical key is required to open/close the doors.| Limited Range |Economical | We have to wait for the current command to be executed or wait for certain time to give next command otherwise it would not be executed|
|Manage all the actions by  buttons. | Have to wait for certain time to use other feature| Can be used whenever we need to know the security status of something| |   
|Encryption in Data. | |  | 

## High Level Requirements

| ID  | High Level Requirement |
| ------------- | ------------- |
| HLR1  | Able to print Window status of the car |        
| HLR2  | Able to print Alarm status the car |          
| HLR3  | Able to print Car battery info|    
| HLR4 | Able to print Door status of the car|

## Low Level Requirements
| ID  | Low Level Requirement | HLR ID
| ------------- | ------------- | ------- |
| LLR1  | If the Button is pressed ONCE, ON LED ORANGE, GREEN along with other LED's | HLR1 |    
| LLR2  |If the Button is pressed ONCE, ON LED RED, BLUE along with other LED's | HLR1|
| LLR3  |If the Button is pressed TWICE, OFF LED ORANGE, GREEN along with other LED's | HLR2 |    
| LLR4  |If the Button is pressed TWICE, OFF LED RED, BLUE along with other LED's | HLR2|
| LLR5  |If the Button is pressed THRICE, ON All LED's in CLOCKWISE manner GREEN-> ORANGE-> RED-> BLUE-> GREEN | HLR3 |    
| LLR6  |If the Button is pressed FOUR TIMES, ON All LED's in ANTI-CLOCKWISE manner GREEN-> BLUE-> RED-> ORANGE-> GREEN | HLR4 |