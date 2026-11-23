---
title: Team Block Diagram
---

## Introduction
As team 206 we are building an automated pet feeder that will not only dispense food but will also monitor how low the food is and alert the user with LEDs and a speaker. Our system is split into three subsystems controlled by their own microchips:
**Justin Gonzalez - Sensors and User Input:** _Uses three photoresistors which detect food level, two buttons for user input and three status LEDs._,
**AJ Bowers - Motor control:** _Drives the motor that will rotate the part that dispenses the food._,
**Donovan Belt - Audio:** _Uses an audio amplifier driving the speaker to play a chime for feeding._
The boards are connected in which AJ's board is the main hub in the middle, allowing Justin and Donovan boards to connect through an 8-pin ribbon cable, while reserving all pin 8's for ground. Every ribbon cable pin connects to the microcontroller so that all communication between the subsystems goes through it instead of being wired directly to the sensors or actuators.

## Team Block Diagram

<img width="1992" height="760" alt="Team_Block_Diagram_304 drawio (2)" src="https://github.com/user-attachments/assets/fecc6ee4-3756-41da-a4a0-25badb41b9b8" />



Figure 1: Image of the team's block diagram

[Link to Team Block Diagram .drawio](https://drive.google.com/file/d/1Mx9VroMIKU4P2QoKEfkzI6bq_MwS5psE/view?usp=sharing)

## Team Connection
Connector between Justin and AJ
|**Pin**   |**From**  | **To**   | **Type** |**Description**|
|----------|----------|----------|----------|----------|
|1|-|-|-|not used|
|2|-|-|-|not used|
|3|Justin (RB2)|AJ (RF6)|0V / 5V Digital| Spare digital signal |
|4|Justin (RC2)|AJ (RF4)|0V / 5V Digital|Send fill signal from when empty is exposed until top sensor is covered |
|5|Justin (RC3)|AJ (RF6)|0V / 5V Digital| Spare digital signal|
|6|-|-|-|not used|
|7|-|-|-|not used|
|8|Ground|Ground|Ground|Ground|



<!-- 
![showcase](../image/innovation_showcase_Sp-2025.jpg)  
**Figure 3:** Innovation Showcase Spring '25, where the products were a STEM-themed display that demonstrates a single scientific/engineering concept with the intended user of K-12 students interested in learning about science, technology, engineering, or math. -->


## Results

1. Numbered Point 1
1. Numbered Point 2
1. Numbered Point 3

## Conclusions and Future Work

[## External Links

[example link to idealab](https://idealab.asu.edu)
](https://drive.google.com/file/d/1Mx9VroMIKU4P2QoKEfkzI6bq_MwS5psE/view?usp=sharing)

## Results

1. Numbered Point 1
1. Numbered Point 2
1. Numbered Point 3

## Conclusions and Future Work

## External Links

[example link to idealab](https://idealab.asu.edu)


## References


