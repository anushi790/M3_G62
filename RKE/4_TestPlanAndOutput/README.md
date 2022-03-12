# TEST PLAN AND OUTPUT

## TC_1 : NUMBER OF TIMES BUTTON PRESSED FOR LOCKING AND UNLOCKING

| TEST ID | Test Case Objective | Input Data  | Expected Output |Actual output| Status|
| ----- | ----- | ------- | ------- | ------ |------ |  
|TC_1.1| Pressed Lock button one time | RF | LOCK CAR |X | FAIL |
|TC_1.2| Pressed Unlock button one time | RF | UNLOCK CAR | X | FAIL|
|TC_1.3| Pressed Lock button two times | RF | ALARM ACTIVATE/DEACTIVATE| X | FAIL|
|TC_1.4| Pressed Unlock button two times| RF | APPROACH LIGHT | X |FAIL|

## TC_2 : NUMBER OF TIMES BUTTON PRESSED LEDS
| TEST ID | Test Case Objective | Input Data  | Expected Output |Actual output| Status|
| ----- | ----- | ------- | ------- | ------ |------ |  
|TC_2.1| Pressed Lock button one time | RF | ALL LEDS ON |X | FAIL |
|TC_2.2| Pressed Unlock button one time | RF | LED blinking clockwise | X | FAIL|
|TC_2.3| Pressed Lock button two times | RF | LED blinking anti-clockwise| X | FAIL|
|TC_2.4| Pressed Unlock button two times| RF | ALL LEDS OFF | X |FAIL|
