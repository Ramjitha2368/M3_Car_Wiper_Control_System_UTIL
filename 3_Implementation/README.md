# Implementation
The implementation part deals with the real time environment.
Power supply is given to the micro controller and the action is
taken by the viper motor according to the program dumped on the
micro controller. It is are of two types they are
* Hardware Implementation
* Software Implementation
## Hardware Implementation
The basic control units of the hardware comprises of power
supply unit, control switch, wiper motor, rain detector sensor
,motor driver circuit and the most important of all pic controller.
Power supply unit maintains the continuous power to the
controller and the wiper motor. Control switch is directly
connected to the controller. Motor driver circuit is linked with
the wiper motor and the controller. The command it gets from the
controller is used to either drive the wiper motor or switch it off.
Rain detection sensor detects the amount of moisture on the
windscreen and accordingly sends the signal to the controller. a
wiper motor control using a load sense resistor to monitor
conditions confronting the wiper operation.

![hardwareimplementation](https://user-images.githubusercontent.com/101034610/168284596-f54a4310-4ef7-4838-bec4-86fcd8b5dd47.png)

## Software Implementation
First initialization of ports A and D as input port and output port
respectively of the ADC was done. Now switch is checked for
it’s ON or OFF status. If the switch is not ON the ports A and D
are initialized again. And if the switch is ON, condition of the
rain is checked whether it’s raining heavily or not. If yes, motor
is turned on at the high speed and if the rain is not heavy, the
motor speed is set to low. Delay is given after each stroke of the
wiper blade and when there is no moisture left on the
windscreen, motor is turned OFF.The delay sub routines are
initialized before the main program is written. Vref=Vdd=5v has
been set in the ADC. Now the analog-to-digital (A/D) Converter
module has eight input channels for the PIC18F458 devices. This
module has the ADCON0 and ADCON1 register definitions that
are compatible with the PICmicro® mid-range A/D module. The
A/D allows conversion of an analog input signal to a
corresponding 10-bit digital number. The A/D module has four
registers. These registers are: A/D result high resistor, A/D result
low resistor, A/D control resistor 0 and A/D control resistor 1. 

![softwareimplementation](https://user-images.githubusercontent.com/101034610/168284808-f9f10ec3-0530-4c3b-8ca9-63cf1a334b9c.png)
