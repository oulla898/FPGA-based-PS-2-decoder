# Automatic Weather-Sensitive Door Closure System

## Abstract

This project develops an effective solution to address the challenge of unpredictable weather in Oman. The system is designed to automatically close doors or windows in response to adverse weather conditions, potentially saving property owners significant money and time by preventing water damage to sensitive equipment and property.

## Problem Description

Unpredictable weather in Oman has led to catastrophic consequences, with a single cyclone causing $162 million USD in property losses. This project aims to mitigate such losses by implementing a system that detects impending bad weather and automatically closes water entrances in homes and offices.

## Introduction

The project brings to life the concept of doors automatically shutting during rainstorms to protect homes and improve lifestyle. This weather-triggered door-closing system is no longer science fiction but a practical reality.

## Design

The system uses two analog sensors:
1. Force Sensor (FSR 406) - to detect wind and rain
2. Light Sensor (LDR) - to understand ambient light conditions

Key components:
- Microcontroller (AVR)
- Transistor-controlled motor
- Pierced cup placed on the force sensor
- Pulley system for increased torque

The system operates differently based on the time of day:
- Nighttime: Triggered by force alone
- Daytime (cloudy): Checks both light and force, triggered at lower force thresholds

## Implementation

The circuit incorporates:
- Two analog sensors (FSR 406 and LDR)
- Microcontroller as the main control unit
- Transistor gate to control motor current
- Motor for mechanical door closure

Laboratory testing confirmed the design's effectiveness, with the system responding appropriately to simulated weather conditions.

## Simulation

Due to the unavailability of the FSR 406 in Proteus, the force sensor was simulated using an LDR. The simulation demonstrated the system's ability to detect specific voltage conditions from the sensors and activate the motor to close the door.

## Conclusion

The project successfully developed a system capable of detecting adverse weather conditions in Oman using sensor technology integrated with mechanical mechanisms. Key achievements include:

- Fast and appropriate response to simulated weather conditions
- Functionality in various lighting conditions (day, night, and overcast)
- Protective mechanism to prevent motor damage
- Potential for real-world application

## References

1. Atlas Magazine - Cyclone Shaheen in Oman: 162 million USD of insured losses
2. Interlink Electronics - FSR 406 Data Sheet
3. Mazidi, M. A., Naimi, S., & Naimi, S. (2017). The AVR microcontroller and embedded systems using assembly and C. Pearson Education.

## Project Team

- Al Muala Talal Almaawali (ID: 135591)
- Omar Masoud Alalawi (ID: 123901)

*Sultan Qaboos University, Department of Electrical and Computer Engineering*
*Course: ECCE4227 - Embedded Systems*
