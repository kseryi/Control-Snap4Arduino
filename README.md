http://s-team.cc.ua/control/index.html

I present to you the control panel designed for the HTTP server environment of Snap4Arduino. Currently, only 4 types of controls have been created:

Slider

Gamepad

Joystick 1

Joystick 2

In the project, buttons send network messages, while joysticks and sliders transmit values of respective variables.

Please note that in the Snap4Arduino program, messages and variable names should start with the symbol "+."

To connect the control panel, you need to be on the same local network as the computer running Snap4Arduino. Make sure that the computer is turned on.

To get started, select the type of control. Check if your device is on the same local network as the Snap4Arduino HTTP server (make sure it is turned on). Then enter the corresponding IP address in the field. Verify the transmission of messages or variables.

Slider

Presented in two groups - PWM and Servo
PWM transmits values ​​in the range from 0 to 255
Servo in the range from 0 to 180
To receive data from the slider in the Snap4Arduino environment, you need to
create corresponding variables

For PWM:
"+pwm1", "+pwm2", "+pwm3"

For Servo:
"+servo1", "+servo2","+servo3"
