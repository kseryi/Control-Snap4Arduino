
For working with smartphones and tablets, I recommend using the Mozilla Firefox browser.

I present to you the control panel designed for the HTTP server environment of Snap4Arduino. Currently, only 4 types of controls have been created:

Slider

Gamepad

Joystick 1

Joystick 2

In the project, buttons send network messages, while joysticks and sliders transmit values of respective variables.

Please note that in the Snap4Arduino program, messages and variable names should start with the symbol "+."

To connect the control panel, you need to be on the same local network as the computer running Snap4Arduino. Check if the HTTP server is enabled.

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

Gamepad

The gamepad has a classic appearance.
It has 12 primary buttons that can transmit messages.
This means that Snap4Arduino can receive 12 different messages depending on which button is pressed.

List of messages: "+L1", "+L2", "+R1", "+R2", "+up", "+down", "+left", "+right", "+square", "+triangle", "+circle", "+cross"

Joystick

Implemented in the form of a game joystick and transmits coordinate values for the variables "+X" and "+Y".

Joystick 2

This is a combination of a joystick and a gamepad.

On the left side is a joystick that transmits values for the variables "+X" and "+Y".

On the right side are buttons that transmit the corresponding messages: "+R1", "+R2", "+square", "+triangle", "+circle", "+cross".
