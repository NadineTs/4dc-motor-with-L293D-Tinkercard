# 4 DC-motor-with-L293D-Tinkercard


## Overview
This project demonstrates how to control four DC motors using the L293D motor driver with an Arduino. The motors will perform a series of movements: moving forward, backward, and alternating turns left and right.

## Components Required
- Arduino Uno
- 4 DC motors
- L293D Motor Driver
- Power supply for motors
- Breadboard and jumper wires

## Circuit Diagram


Ensure to connect the motors and the L293D driver according to the provided circuit diagram.


## Code Explanation

### Setup Function
The `setup()` function initializes the motor control pins as outputs and ensures that all motors are stopped initially.

### Loop Function
The `loop()` function carries out the following movements in sequence:
1. Move forward for 30 seconds.
2. Move backward for 1 minute.
3. Alternate turns left and right for 1 minute.

### Motor Control Functions
- **moveForward()**: Activates all motors to move forward.
- **moveBackward()**: Activates all motors to move backward.
- **turnRight()**: Activates motors to turn right.
- **turnLeft()**: Activates motors to turn left.
- **stopMotors()**: Stops all motors.
- **alternateRightLeft()**: Alternates between turning right and left every second for 1 minute.

