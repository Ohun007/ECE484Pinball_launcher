# ECE484Pinball_launcher

This repository holds the code for our ECE484 Pinball machine's launch control.
This project uses a solenoid controlled by an Arduino mega. The button on the machine is software debounced and is an active high button that sends a signal to the Arduino.
The Arduino is connected to a relay that allows it to control the solenoid, as the solenoid is driven by 36v. The solenoid being driven by the Arduino allows for greater functionality,
such as multi-ball mode, that can be automatically trigger by playfield conditions.
