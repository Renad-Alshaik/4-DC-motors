# 4-DC-motors

Programming 4 DC motors using the L293D motor driver to perform the following movements: 
1- Forward for 30 seconds 
2- Backward for a minute 
3- Alternate right and left for a minute

# circuit connections
1- Arduino Uno: The central microcontroller manages the motor control signals. Digital pins on the Arduino are connected to the input pins of the L293D ICs to control the motor directions and speeds.

2- L293D Motor Drivers: Two L293D ICs are used, each capable of driving two motors. They serve as an interface between the Arduino and the motors, providing the necessary current and voltage to drive the motors:.
* The input pins of the L293D are connected to Arduino digital output pins.
* The output pins of each L293D are connected to the DC motors.
* The enable pins of the L293D are likely tied to either a high signal or controlled via PWM to manage motor speed.

3- Motors: Four DC motors are connected to the output terminals of the L293D ICs. These motors receive signals from the ICs to operate at the desired speed and direction.

4- Power Supply: A 9V battery is used as the main power source for the motors, connected via the breadboard's power rails. This ensures the motors receive adequate voltage while the Arduino is powered through USB or a separate power source.

5- Breadboard: The breadboard facilitates easy wiring, acting as a hub for connecting components. It is used to distribute power from the battery and manage connections between the Arduino, motor drivers, and motors.
