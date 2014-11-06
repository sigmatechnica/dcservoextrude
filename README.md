dcservoextrude
============

Arduino sketch to drive an extruder for a FDM 3D printer fitted with a DC motor and quadrature encoder with step / direction signals like it is a stepper motor.  Based on  https://github.com/cswiger/dcservodrive

Requires libraries:
FlexiTimer2.h   http://playground.arduino.cc/Main/FlexiTimer2<br/>
PID_v1.h        http://playground.arduino.cc/Code/PIDLibrary<br/>
AFMotor.h       https://github.com/adafruit/Adafruit-Motor-Shield-library PLUS  my own custom version hacked to work with ardumoto from sparkfun:  https://www.sparkfun.com/products/9815<br/>
Encoder.h       http://playground.arduino.cc/Main/RotaryEncoders</br>

For only one motor, the basic arduino Uno will work, but for more than one motor something like a mega2560 is needed so the interrupts and motor pwm don't conflict. 

