# M3_Car_Wiper_Control_System_UTIL
# Car Wiper Control system
# Introduction
All automotive industries seek to provide low cost system for
all the applications including automatic wiper system in vehicle.
In recent time automotive industries focusing on autonomous
vehicle which means self-drive system on different applications.
For this scenario, this paper offers low cost wiper system with
simple and effective concept of electro mechanical concept to wipe
the windscreen automatically. Automatic wiping has been done
during rainfall without human interrupt. Thus an uninterrupted
makes to avoid distraction of the drive and secure from accidents.
Nowadays vehicles are more automated whereas the cost of the
embedded system used for different critical applications are too
high. Basically, increase in technology will enhance the vehicle
cost. This criterion makes to develop low cost automatic wiper
system. The wiper system has been implemented to forecast in
all low cost vehicles.
In the current scenario, only luxury vehicles employ intelligent
rain sensing wind shield Wiper systems. Our system is modelled to
demonstrate how useful is an automatic wiper system that adjusts
speed itself based on rainfall intensity. Such a system improves
the safety of a ride.
An automatic, intelligent system like ours removes any manual
errors. Our system adjusts wiper speed according to the intensity
of rainfall and hence improves the safety.

# Exploring STM32F407 Discovery Board
The main purpose of this project is to get an insight into the STM32F407 Discovery Board, which is an ARM Cortex M4 based Microcontroller. As I started working on STM32F07 Discovery Board, initially it was difficult and confusing to understand and program this microcontroller because understanding internal structures and working of the microcontroller using datasheet of STM32F407VGT MCU is difficult especially if one is a beginner.

![STM DISCOVERY BOARD](https://user-images.githubusercontent.com/101034610/168224946-7c8d1b47-29b8-4465-9784-8f1e5c617baa.jpeg)

# AN EMBEDDED SYSTEM
An embedded system is a microprocessor-based computer hardware system with software that is designed to perform a dedicated function, either as an independent system or as a part of a large system. At the core is an integrated circuit designed to carry out computation for real-time operations.
An embedded system has three components

* It has hardware.
* It has application software.
* It has Real Time Operating system (RTOS) that supervises the application software and provide mechanism to let the processor run a process as per scheduling by following a plan to control the latencies. RTOS defines the way the system works. It sets the rules during the execution of application program. A small scale embedded system may not have RTOS.
The block diagramof embedded system are
![Block diagram of Embedded system](https://user-images.githubusercontent.com/101034610/168228130-826125dc-ff05-4578-861b-ed2d4830a86b.jpeg)

# Define System
The basic wiper control system design is given by,

![wiper system](https://user-images.githubusercontent.com/101034610/168254645-8d561770-d0ee-48a3-beb2-e416f53592fc.jpeg)

![wiper switching operation](https://user-images.githubusercontent.com/101034610/168254739-15013070-ab91-45b7-bf6c-30f4c3046756.jpeg)

# Specifications
The following are the major specifications to develop car wiper control system.They are,
* Hardware
     * STM32F4 Microcontroller
     * USB Cable
     * Push Button or Switch
     * Timer
     * power Supply
     * LEDs
* Software
     * QEMU Software
     * STM32cubeMX
* Embedded C Language
# Details of Components
## STM32F4 Microcontroller
The STM32 F4-series is the first group of STM32 microcontrollers based on the ARM Cortex-M4F core. The F4-series is also the first STM32 series to have DSP and floating-point instructions. The F4 is pin-to-pin compatible with the STM32 F2-series and adds higher clock speed, 64 KB CCM static RAM, full-duplex I²S, improved real-time clock, and faster ADCs. 
## USB Cable
The term USB stands for "Universal Serial Bus". USB cable assemblies are some of the most popular cable types available, used mostly to connect computers to peripheral devices such as cameras, camcorders, printers, scanners, and more.

By using USB cable dump the sofware code on to hardware kit.
## Push Button or Switch
A Push Button switch is a type of switch which consists of a simple electric mechanism or air switch mechanism to turn something on or off. Depending on model they could operate with momentary or latching action function. The button itself is usually constructed of a strong durable material such as metal or plastic.
## Timer
A timer is a specialized type of clock which is used to measure time intervals. A timer that counts from zero upwards for measuring time elapsed is often called a stopwatch. It is a device that counts down from a specified time interval and used to generate a time delay, for example, an hourglass is a timer.
## LEDs
A Light Emitting Diode (LED) is a semiconductor device, which can emit light when an electric current passes through it. To do this, holes from p-type semiconductors recombine with electrons from n-type semiconductors to produce light.
## Power Supply
A power supply is an electrical device that supplies electric power to an electrical load. The main purpose of a power supply is to convert electric current from a source to the correct voltage, current, and frequency to power the load. As a result, power supplies are sometimes referred to as electric power converters.

# Conclusion

## Conclusion
All the results are tested positive and hardware’s are working
fine in real time environment as far as test was done. It will give
a new dimension of comfort and aid to the drivers who work at
night and traffic prone areas where they already have to
concentrate on brakes and clutch. The removal of controlling the
wipers during rain will provide them much ease and help them
concentrate on the basic ABC (accelerator, brake and clutch) of
driving.


# Folder Structure
|Folder  |Description  |
|--------|-------------|
|0_Abstract|Aim and Goal of the project|
|1_Requirements|Documents Specifying the detailed components to build this project|
|2_Architecture|This Folder having documents and they specify architecure and control flow and design flow|
|3_Implementation|Documentes requires src files and souce code,Doxygen and Makefile|
|4_TestPlan and Output|Douments with test plans and procedures|
|5_Report|Decumentation specifying  report on project|
|6_simulation|The documents require the images and videos|

# SDLC ACTIVITY

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/334e3ba784d945a6b21852ba7de5fb5c)](https://app.codacy.com/gh/Ramjitha2368/M3_Car_Wiper_Control_System_UTIL?utm_source=github.com&utm_medium=referral&utm_content=Ramjitha2368/M3_Car_Wiper_Control_System_UTIL&utm_campaign=Badge_Grade_Settings)
[![CI](https://github.com/Ramjitha2368/M3_Car_Wiper_Control_System_UTIL/actions/workflows/CI.yml/badge.svg)](https://github.com/Ramjitha2368/M3_Car_Wiper_Control_System_UTIL/actions/workflows/CI.yml)

[![Build windows](https://github.com/Ramjitha2368/M3_Car_Wiper_Control_System_UTIL/actions/workflows/Build%20Windows.yml/badge.svg)](https://github.com/Ramjitha2368/M3_Car_Wiper_Control_System_UTIL/actions/workflows/Build%20Windows.yml)

[![Build Linux](https://github.com/Ramjitha2368/M3_Car_Wiper_Control_System_UTIL/actions/workflows/Build%20Linux.yml/badge.svg)](https://github.com/Ramjitha2368/M3_Car_Wiper_Control_System_UTIL/actions/workflows/Build%20Linux.yml)

[![Cpp Check](https://github.com/Ramjitha2368/M3_Car_Wiper_Control_System_UTIL/actions/workflows/Cpp%20Check.yml/badge.svg)](https://github.com/Ramjitha2368/M3_Car_Wiper_Control_System_UTIL/actions/workflows/Cpp%20Check.yml)

[![Contribution Check -Git Inspector](https://github.com/Ramjitha2368/M3_Car_Wiper_Control_System_UTIL/actions/workflows/Contribution%20Check%20-Git%20Inspector.yml/badge.svg)](https://github.com/Ramjitha2368/M3_Car_Wiper_Control_System_UTIL/actions/workflows/Contribution%20Check%20-Git%20Inspector.yml)

[![Static Check](https://github.com/Ramjitha2368/M3_Car_Wiper_Control_System_UTIL/actions/workflows/Static%20Check.yml/badge.svg)](https://github.com/Ramjitha2368/M3_Car_Wiper_Control_System_UTIL/actions/workflows/Static%20Check.yml)

[![Dynamic Check](https://github.com/Ramjitha2368/M3_Car_Wiper_Control_System_UTIL/actions/workflows/Dynamic%20Check.yml/badge.svg)](https://github.com/Ramjitha2368/M3_Car_Wiper_Control_System_UTIL/actions/workflows/Dynamic%20Check.yml)

[![Unity Testing](https://github.com/Ramjitha2368/M3_Car_Wiper_Control_System_UTIL/actions/workflows/Unity%20Testing.yml/badge.svg)](https://github.com/Ramjitha2368/M3_Car_Wiper_Control_System_UTIL/actions/workflows/Unity%20Testing.yml)

[![Valgrind](https://github.com/Ramjitha2368/M3_Car_Wiper_Control_System_UTIL/actions/workflows/Valgrind.yml/badge.svg)](https://github.com/Ramjitha2368/M3_Car_Wiper_Control_System_UTIL/actions/workflows/Valgrind.yml)
