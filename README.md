# Servo_Motor_Interfacing

**NAME**: ADITYA GANGURDE
**DOMAIN**: Embedded Systems
# DESCRIPTION : This project is performed to impliment and understand how to control the rotation angle of a servo motor using a potentiometer, interfaced with an Arduino UNO, allowing smooth manual position control.

**Components Used**: 
1.Arduino UNO Board
2.Servo Motor (SG90 or similar)
3.Potentiometer (10kΩ)
4.Breadboard
5.Jumper Wies
6.USB Cable (for Arduino power and programming)

**Working Principle**:
A potentiometer acts as a variable voltage divider, providing an analog voltage input to the Arduino. The Arduino reads this analog value (0-1023) from the potentiometer through Analog Pin A0. Using the map() function, this range is scaled to the servo motor's rotational range (0° to 180°). The servo motor is controlled via Digital Pin 9 (PWM), adjusting its shaft position based on the potentiometer's rotation. As the potentiometer is turned, the servo motor rotates proportionally.

**Applications**:
1.Manual servo position control.
2.Learning basics of analog-to-digital conversion (ADC) in Arduino.
3.Robotics: Joint or arm control.
4.DIY projects like Camera Pan-Tilt mechanisms.

**Output** :
