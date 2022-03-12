# BICOM SYSTEM

## DESCRIPTION

Bi-Com system is an extension of uni-directional Remote Keyless Entry(RKE) to bi-directional RKE. Remote Bi-Com is an electronic access system that is used to perform specific funtions and  require the end user to initiate an action. Here, the communication is not only from key fob to car but also from car to key fob. Some of the additional features supported in Bi-com are to get the information about status of car which includes window status, alarm status, battery information and door status.

## IDENTIFYING FEATURES
By pressing the button:
- It prints the window status whether it is on or off.
- It also prints/displays about the alarm status. 
- It also displays about the car battery information.
- It also shows the door status of a car whether open or not.

## REQUIREMENTS

### High Level Requirements

High Level Requirement ID     | Description |
-------| -----------------------------------------|
HLR_1  |Get the status of car windows|
HLR_1  |Get the status of car alarm|
HLR_1  |Get the information about car battery|
HLR_1  |Get the status of car door|

### Low Level Requirements


| ID | Low Level Requirements for HL_1|       |ID | Low Level Requirements for HL_2|
| -------- | -------------- | ---- |-------- | -------------- |
| LLR_1.1 |  Check if button is pressed once  | | LLR_2.1 | Check if button is pressed twice |
| LLR_1.2 | Clear the state of LEDs || LLR_2.2 | Clear the state of LEDs   |
| LLR_1.3 | Switch ON all LEDs at the same time || LLR_2.3 |Switch OFF all LEDs at the same time   |

| ID | Low Level Requirements for HL_3|       |ID | Low Level Requirements for HL_4|
| -------- | -------------- | ---- |-------- | -------------- |
| LLR_1.1 |  Check if button is pressed thrice.  | | LLR_2.1 | Check if button is pressed four times. |
| LLR_1.2 | Clear the state of LEDs || LLR_2.2 | Clear the state of LEDs   |
| LLR_1.3 | Switch ON all LEDs in clockwise pattern || LLR_2.3 |Switch ON all LEDs in anti-clockwise direction.  |


## SWOT ANALYSIS
![1](https://user-images.githubusercontent.com/46949702/157812922-1a8d62fa-e311-4544-9604-b67284372456.png)

## 5W's 1H

- What - Bi-Directional system which support information exchange and control from key fob to car or car to key fob. 

- Why - For easy accessibility of the features without the physical contact.

- Where - Anywhere when user wishes.

- When - Anytime in a day when he wants to get information of car status or control car. 

- Who - Person who has a car.

- How - By using the keyfob a remote controlled device.

