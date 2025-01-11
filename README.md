In this project i will tell you how to make Line Following Robot Using Arduino which is used arduino uno smd board.this project we used parts as follow

    Arduino Uno smd
    L298n Motor Driver
    IR Proximity Sensors x3
    batteries 4 volt x2  in series
    connecting wires
    switch on/off
    2 wheel car Chassis

What is Arduino UNO?

    Before diving deep into the discussion let us first have understanding about what the Arduino is?
    The Arduino is the open source microcontroller development board based on the ATMEGA328P microcontroller IC designed to provide the simple and cheap platform 
    to the hobbyists and students for designing their digital and embedded systems projects.
    The ATMEGA328P microcontroller IC is the heart of the Arduino microcontroller development that is the board is designed around the ATMEGA328P microcontroller IC.
    The Arduino UNO microcontroller development looks like the one in the above image.
![arduino-pin-diagram](https://github.com/user-attachments/assets/a868ea04-bb41-42fb-b475-ab67de20858f)

       

Arduino Integrated Development Environment (IDE):

    Arduino UNO is quite easy to program. As most of you might have known that in order to program a microcontroller one need to write the code in the editor, and then 
    compile that code in the compiler after which you get the HEX file of that code and later upload that HEX file in the microcontroller IC using another program. 
    In case of Arduino all these steps are performed in single software which is called the Arduino IDE. By integrated Development Environment it means that all the 
    steps that editor, compiler, burner are integrated in the same software. In short Arduino UNO is quite easy to program it is just a matter of few clicks. 
![Arduino-IDE](https://github.com/user-attachments/assets/5402362c-9ddf-4dfa-a13f-6837eb286979)

Arduino UNO features

    
    Microcontroller IC                               Microchip ATmega328P

    Operating Voltage                                5 Volts

    Input Voltage                                    7 to 20 Volts (Note that this voltage would be apply to the jack only and not on the power supply 
                                                     pins available on the header).

    Digital I/O Pins                                 14 (of which 6 provide PWM (Pulse Width Modulation) output)

    Analog Input Pins                                6

    DC Current per I/O Pin                           20 mA (This is the current that can be sourced or sink into and out of the Input / Output pins)

    DC Current for 3.3V Pin                          50 mA

    Flash Memory                                     32 KB of which 0.5 KB used by bootloader

    SRAM                                             2 KB

    EEPROM                                           1 KB

    Clock Speed:                                     16 MHz (All the operations are synced by this clock)


L298 Motor driver

    L298 is basically the Integrated Circuit chip that is used to drive the DC motors.
    The chip is designed in such a way so as to control two DC motors simultaneously and in addition control the direction of rotation of each motor
    The L298 IC is a high current, high voltage full bridge driver designed to accept the standard TTL (Transistor-Transistor Logic) logic. The chip is optimized 
    to drive the inductive loads such as relays, solenoids and DC motors.
    The L298 chip looks like the one in the following image:
![L298-Motor-driver-768x421](https://github.com/user-attachments/assets/f17e46b3-863c-43c4-9afe-c0d18d7b919f)

L298n Motor Driver Specification

    As we saw in the previous discussion that the L298 is the motor driver IC but usually it is available in the modular form which is ready to plug and play.
    The module of L298 motor driver looks like the one in the following image:
    The control pins, output pins and the power pins are available at the connectors of the module. Let us consider the working if each pin in detail.

INPUT1 pin of l298n

    This pin along with the INPUT2 pin is used to control the direction of the motor 2.
INPUT2:

    This pin along with the INPUT1 pin is used to control the direction of the motor 2.
INPUT3:

    This pin along with the INPUT4 pin is used to control the direction of the motor 1.
INPUT4:

    This pin along with the INPUT3 pin is used to control the direction of the motor 1.
ENABLEA:

    This pin is used to enable the driver of the motor 2. This pin is made HIGH by default in module with the help of the jumper.
ENABLEB:

    This pin is used to enable the driver of the motor 1. This pin is made HIGH by default in module with the help of the jumper.
    
![Pin-Configuration-of-the-L298-Motor-Driver](https://github.com/user-attachments/assets/4664e58e-ca7e-410f-a1c6-dc180bb41822)

what is IR sensor:

    Before diving deep into the discussion on the simulation of IR sensor let us first see what is the IR sensor? IR sensor as the name implies is the 
    type of sensor that is used to detect the presence of the infrared radiation in the vicinity of the sensor. The IR sensor can be considered as simply 
    an IR led which measures or respond to the IR waves. Infrared radiation as most of you might know is the electromagnetic wave in a particular frequency 
    range in the Electromagnetic Spectrum.

![IR-sensor-1024x469](https://github.com/user-attachments/assets/4f00e0e9-dad0-43c6-bd2d-a423eb356087)

Working Principle of the Proximity Sensor:

    The working principle of the Proximity sensor is quite simple. As shown it is based on the IR receiver and transmitter. The transmitter of the proximity sensor 
    emits the infrared radiation in the surrounding and the receiver then responds to the IR waves that get reflected from the reflecting surface. The IR waves are 
    usually absorbed by the black colored surface and reflect from the white color surface. This response of the IR radiation makes the IR sensor to be used in line 
    following robots which will be covered in next post.

![Proximity-Sensor-768x359](https://github.com/user-attachments/assets/49d7901f-48b3-4b69-9123-507fa0830515)

References :

https://projectiot123.com/2019/03/25/l298-motor-driver-simulation-in-proteus
    

