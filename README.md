# Layan_task2_Arduino
I created an Arduino project where three LEDs turn on when a button is pressed, and turn off when the same button is pressed again.
I created an Arduino project where three LEDs are connected to pins 13, 12, and 11, and a push button is connected to pin 2. The goal of this project is to control the ON/OFF state of all three LEDs using just one button.

When I press the button once, all three LEDs turn on at the same time. When I press the button again, all three LEDs turn off. Each press toggles the LEDs between ON and OFF.

In the code, I used a Boolean variable to keep track of whether the LEDs are currently on or off. I also used digitalRead() to check the button state and digitalWrite() to control the LEDs. The button input is read using the internal pull-up resistor by setting INPUT_PULLUP mode, and a simple debounce delay is added to avoid multiple triggers from one press.

This project helped me understand how to use buttons for toggling outputs, how to read input states
