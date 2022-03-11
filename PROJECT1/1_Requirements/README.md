# REQUIREMENTS    
## Introduction

This is a project based on REMOTE KEYLESS ENTRY which helps to unlock 
and lock the car doors with other functions also like turning Off/On Alarm and
nearby approach. Remote keyless entry system contain a short-range radio transmitter,
and must be within a certain range, usually 5-20 meters, of the car to work.
When a button is pushed, it sends a coded signal by radio waves to a receiver 
unit in the car, which will do the preferred functions.

## INPUT FUNCTIONS
* In SINGLE click, the car will be loacked
* In DOUBLE clicks, the car will be unlocked
* In TRIPLE clicks, On/OFF of the alarm system of the car
* In QUADRUPLE clicks, Theft security system activated

## STATE OF ART
* Buttons and LED's are installed in REmote keyless entry system
* Lock/Unlock, Alarm and Approach light Activation/Deactivation are provided
* Transmitter is provide to transmit the signal
* Receiver provided to receive the signal

## 5W's and 1H
![5W 1H](https://user-images.githubusercontent.com/98849090/157836438-4c969c68-5645-494f-b818-9c52547a2ef7.png)



## SWOT
![SWOT](https://user-images.githubusercontent.com/98849090/157830209-d6c72982-d75f-49db-a9d3-d8c878601228.png)

# High Level Requirements

|Id|High Level Requirements|
|---|-----------------------|
|HLR1|It shall print window status of the car|
|HL02|It shall print alarm status of the car|
|HL03|It shall print car battery information|
|HL04|It shall door status of the car|

# Low Level Requirements

|Id|Low Level Requirements for HL1|ID|Low Level Requirements HL2|
|---|-----------------------|--|----------------------------|
|LLR1.1|If the switch is pressed once, ON all LED's	|LLR2.1|If the switch is pressed twice, OFF LED's|


|Id|Low Level Requirements for HL3|ID|Low Level Requirements HL4|
|---|-----------------------|--|----------------------------|
|LLR3.1|If the switch is pressed three times, ON all LED's in clockwise manner|LLR4.1|If the switch is pressed FOUR times, ON all LED's in anti-clockwise manner|
