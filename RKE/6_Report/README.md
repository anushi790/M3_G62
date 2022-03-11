## About
RKE (Remote Keyless Entry) is a smart entry system which is an electronic lock that control access to a vehicle without using a traditional mechanical key. It doesn't rely on a physical button or panel in order to get into your vehicle, instead it has a sensor that detects your remote keyless key within range of vehicle.

## Features
- The car will be locked when the lock button is pressed Once.
- The car will be unlocked when the unlock button is presses Once.
- The alarm of the car will be activated/deactivate when the lock button is pressed Twice.
- Approaching lights of the car will be turned ON when the unclock button is pressed TWICE.
## 4 W's and 1-H
| WHO | WHAT | WHEN | WHERE | HOW |
| ------------- | ------------- | ----| ----- | ----- |
| Users who want to control car features(Opening/CLosing doors, Activate/Deactivate alarm, Turning ON approching lights) remotely| Remote Key for car |When user want to use features(Opening/CLosing doors, Activate/Deactivate alarm, Turning ON approching lights) | Inside/Outside of the car| By applying no of pushes on specific button for that feature| 

## SWOT Analysis
| STRENGTHS | WEAKNESSES | OPPORTUNITIES | THREATS |
| ------------- | ------------- | ----| ----- |
| No Mechanical key is required to open/close the doors.| Limited Range |Economical | We have to wait for the current command to be executed or wait for certain time to give next command otherwise it would not be executed|
|Manage all the actions by two buttons. | Have to wait for certain time to use other feature| Can be used in other things such as Building doors where we want to remotely send commands| |   
|Encryption in Data. | Cannot figure out the current status of car|  | 

## High Level Requirements

| ID  | High Level Requirement |
| ------------- | ------------- |
| HLR1  | Able to lock car |        
| HLR2  | Able to unlock car |          
| HLR3  | Able to turn alarm ON/OFF|    
| HLR4 | Able to turn ON approaching lights|

## Low Level Requirements
| ID  | Low Level Requirement | HLR ID
| ------------- | ------------- | ------- |
| LLR1  | If the Lock Button is pressed ONCE, ON LED ORANGE, GREEN along with other LED's | HLR1 |    
| LLR2  |If the Lock Button is pressed ONCE, ON LED RED, BLUE along with other LED's | HLR1|
| LLR3  |If the Unlock Button is pressed ONCE, OFF LED ORANGE, GREEN along with other LED's | HLR2 |    
| LLR4  |If the Unlock Button is pressed ONCE, OFF LED RED, BLUE along with other LED's | HLR2|
| LLR5  |If the Lock  Button is pressed TWICE, ON All LED's in CLOCKWISE manner GREEN-> ORANGE-> RED-> BLUE-> GREEN | HLR3 |    
| LLR6  |If the Unlock Button is pressed TWICE, ON All LED's in ANTI-CLOCKWISE manner GREEN-> BLUE-> RED-> ORANGE-> GREEN | HLR4 |

# Behavioral Diagrams:

## High level Diagram 
![Behavioural Diagram (2)](https://user-images.githubusercontent.com/71927150/157893241-1d7fe4d3-c776-46da-9dee-5d64761ff492.jpg)

## Low level Diagram
![Behavioural Low level Diagram](https://user-images.githubusercontent.com/71927150/157893596-5a904b60-4d56-4466-9ad9-f9f81ce4c656.jpg)

# Structural Diagram:

## High level Diagram
![Structural_diagram HLD](https://user-images.githubusercontent.com/71927150/157898011-bbff5bbf-f9ff-4388-b52f-f7c0a5be217e.jpg)



## Low level Diagram
![structural diagram LLD](https://user-images.githubusercontent.com/71927150/157898036-4e4dd730-a6d0-4aba-b7c4-8ece344fae7b.jpg)

# TEST PLAN AND OUTPUT

## TC_1 : NUMBER OF TIMES BUTTON PRESSED

| TEST ID | Test Case Objective | Input Data  | Expected Output |Actual output| Status|
| ----- | ----- | ------- | ------- | ------ |------ |  
|TC_1.1| Pressed one time | RF | LOCK CAR |X | PASS |
|TC_1.2| Pressed two times | RF | UNLOCK CAR | X | FAIL|
|TC_1.3| Pressed three times | RF | ALARM ACTIVATE/DEACTIVATE| X | PASS|
|TC_1.4| Pressed four times| RF | APPROACH LIGHT | X |FAIL|

## TC_2 : 
| TEST ID | Test Case Objective | Input Data  | Expected Output |Actual output| Status|
| ----- | ----- | ------- | ------- | ------ |------ |  
|TC_2.1| Pressed one time | RF | ALL LEDS ON |X | PASS |
|TC_2.2| Pressed two times | RF | LED blinking clockwise | X | FAIL|
|TC_2.3| Pressed three times | RF | LED blinking anti-clockwise| X | PASS|
|TC_2.4| Pressed four times| RF | ALL LEDS OFF | X |FAIL|
