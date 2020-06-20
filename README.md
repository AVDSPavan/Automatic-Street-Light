# Automatic-Street-Light
It is an Electronic automation project of Automatic street light which is build using Arduino UNO micro controller, Ultrasonic sensors, LED lights and an arduino program.
Every night, we see that Street lights and Lights on Highway roads are switched on whole night and sometimes we will think that how much electricity those all lights are consuming.
From that thought, we build a small prototype solution using automation.
The solution is the lights will be switched on only when an object is detected by the ultrasonic sensors.
It is not like just switch on single light and again switch it off, whenever an object detected by it, it will switch on 4 or 5 lights for certain amount of time near that sensor.
By implementing this type of approach, there will be no problems for vehicle users and also it helps to save power.

Components Used:
Arduino UNO
Ultrasonic Sensors
Light Emitting Diodes (LED)
Jumping wires
Bread board
Connecting Wires
Soldering 


Arduino UNO Micro controller:
The Arduino UNO is a widely used open-source microcontroller board based on the ATmega328P microcontroller and developed by Arduino.cc.
The board is equipped with sets of digital and analog input/output (I/O) pins that may be interfaced to various expansion boards (shields) and other circuits
There are a total of 20 pins which can be used for either output or input.
It is equipped with a USB port,14 digital pins, 6 Analog pins, a 16 MHz crystal oscillator, a USB connection, a power jack, an ICSP header, and a reset button.


Ultrasonic sensors:
The HC-SR04 Ultrasonic Module has 4 pins, Ground, VCC, Trig and Echo. The Ground and the VCC pins of the module needs to be connected to the Ground and the 5 volts pins on the Arduino Board respectively and the trig and echo pins to any Digital I/O pin on the Arduino Board.
It emits an ultrasound at 40,000 Hz which travels through the air and if there is an object or obstacle on its path It will bounce back to the module.
In order to generate the ultrasound you need to set the Trig on a High State for 10 µs. That will send out an 8 cycle sonic burst which will travel at the speed of sound and it will be received in the Echo pin. The Echo pin will output the time in microseconds the sound wave traveled.

Advantages:
Highly sensitive.
Works according to the motion of the object.
Fit and Forget system.
Low cost and reliable circuit.
Complete elimination of manpower.
System can be switched into manual mode whenever required.


Circuit Diagram is placed in the power point presentation. Do the connections as per the diagram.
Use the arduino program to control the lights,sensors and their actions.
Thank You.
