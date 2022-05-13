# Introduction
The wipers are individual controlled by two wiper switches on the P5 fwd overhead panel with the next selections:
*  INT – Intermittent operation, sweeps the wiper every 7 seconds.
* LOW – Low speed operation, sweeps the wiper ± 160 times per minute.
* HIGH – High speed operation, sweeps the wiper ± 250 times per minute.
* PARK – Stops wiper operation

  The windscreen of modern vehicles have a double curvature, which requires long articulated wiper blades with the ability to flex to the contour of the glass. Wiper systems generally use two wipe speeds to suit the driving conditions and also an intermittent wipe facility is incorporated.
A car wiper motor on a modern vehicle should be a high powered quiet unit operating on a current of 2 – 4 A. In the past, shunt-wound motors were used but now-a-days the permanent-magnet motor is commonly used.

![wiper](https://user-images.githubusercontent.com/101034610/168259432-602b4371-d71b-4f13-a29a-5e67999133ae.jpeg)


# Requirements
## High level Requirements
|ID    |Component|Description  |
|------|-------------|---------|
|HLR01|LED |to represent the operation of Microcobtroller |  
|HLR02|Timer|For Setting Delay|
|HLR03|Power Supply|The power supply make the working f hardware |
|HLR04|Frequency|Come on and OFF alternately for set frequency in HZ|
|HLR05|Switch|To make on and off Conditions|

## Low Level Requirements
|ID    |Component         |Description       |
|------|------------------|------------------|
|LLR01 |Regulator         |Regulate the power supply to protect hardware circuit|
|LLR02|ACC  Key           | The Red LED should be On|
|LLR03|Lock Key           |The Red LED Should be Off|

# Swot analysis

![swot analysis](https://user-images.githubusercontent.com/101034610/168082403-c0b70593-361f-42b4-a797-f3e3b27ad115.png)

# 4W'S & 1H

## what
It controls the operational speed of a wiper in accordance with rain conditions

## Where
It is located underneath the dashboard,above the brake & accelerator pedal and
It is used in buses,cars,lorries,vans,etc

## When
The humidity or rain falls the wipers can be used

## Why
To clean the windscreen sufficiently to provide suitable visibility at all times

## How
Wiper system in cars today use a rain sensor to detect the speed at which the raindrops are falling on the windsheild

# STM32F407
The STM32F4 Discovery board is small devices based on STMF407 ARM microcontroller, which is a high-performance microcontroller.  This board allows users to develop and design applications. It has multiple modules within itself which allows the user to communicate and design the interface of different kinds without relying on any third device. The board has all the modern system modules peripherals like DAC, ADC, audio port, UART, etc which makes it one of the best-developing devices. The device may be for developing modern applications but some protocols will need to be followed to use the device, like the compiler, voltage potential, etc. 

# INTRODUCTION TO STM32F407
The STM32F407 belongs to the family of microcontrollers and has a core of ARM cortex-M4 which is based on the RISC (Reduced-instruction-set Computing) structure.
This module comprises of large operating speed embedded memory units such as flash memory having a storage capacity of one megabyte, static random access memory of one ninety kilobytes, with that has four-kilo bytes Static ram as back up memory unit.
There are numerous inputs and outputs pinouts and many external devices can be attached with this module through the APB bus, with the use of 3 AHB bus and thirty two-bit multi AHB bus matrix.
It also comes with 3 twelve but analog to digital converters, 2 digital to analog converter, less power consuming RTC module also installed on this device.
There is 12 GP sixteen bits timer comprises with the 2 pulse width modulation timers which can be used the speed regulation of the motor, also has 2 GP thirty-two bit timers.

![pindiagram](https://user-images.githubusercontent.com/101034610/168267819-5efd8117-479d-46de-a15e-ac82626508c3.jpeg)

# PINCOFIGURATION
The STM32F4 has two male headers P1 and P2, both headers are connected to port A, C, D, E & H which will be used for further functions.
## Power supply pins
This board provides onboard power pins to give power to external sensors or circuits
 ## Power Input
The STM32F4 has multiple power pins are all pins can be used any 5-V power supply to power up the device.  The power-up the whole device only pins can be used, power input through USB won’t be able to activate all modules of the device. All Power input pin is given below:

In P1 Header:

VDD – Pin3, Pin4

In P2 Header:

5V – Pin3, Pin4
VDD – Pin22
## Power Output:
Different power levels have always been a requirement for every device, and to fulfill the requirement there is an internal regulator within the STM32F4. It has two power pin one is 5Volt and the second one is 3V3. 5V pin is directly connected to the power input and 3V3 is connected through the regulator. Both pins are

in header P2:

5V – Pin3, Pin4
3V3 – Pin5, Pin6, GPIO15, GPIO16
## Ground:
In the case of multiple external devices the ground becomes the basic requirement for each device to make the common ground. This device has multiple
ground pins in both headers which can be used individually. All of them are connected internally and they are listed below:

In P1 Header:

GND – Pin1, Pin2, Pin5, Pin23, Pin49, Pin50

In P2 Header:

GND – Pin1, Pin2, Pin49, Pin50

![pinconfig](https://user-images.githubusercontent.com/101034610/168269647-843a9dd4-8725-459f-9e6d-079da330bbc5.jpeg)
