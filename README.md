Project Overview
This GitHub repository hosts a dedicated project designed to showcase the control of an LED and a DC motor using the ATmega32 microcontroller's external interrupts, specifically INT0 for the LED and INT1 for the DC motor. It employs falling edge sense mode activated by switches, providing a hands-on example of hardware control through external interrupts.

Key Features
1-INT0 for LED Control: Utilizes the INT0 external interrupt for toggling the LED state. The falling edge detection on INT0 triggers the LED to switch between on and off states.
2-INT1 for DC Motor Control: Employs the INT1 external interrupt to manage the operation of a DC motor. A falling edge on INT1 activates the motor control, allowing for start/stop actions.
3-Falling Edge Sense Mode: Both INT0 and INT1 are configured to detect falling edges, meaning the actions (LED toggle or motor control) are executed when the signal on the interrupt pin transitions from high to low. This is particularly useful for button-press scenarios where a physical switch can be used to generate the signal.
4-Switch Integration: Demonstrates how to integrate simple mechanical switches to control sophisticated hardware components (LED and DC motor) in an embedded system context.
