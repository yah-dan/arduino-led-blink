# Arduino LED Blink

A beginner electronics project toggling an external LED using an Arduino.

### Parts List
* 1x Arduino board (Uno/Nano)
* 1x 220Ω Resistor
* 1x Red LED
* Breadboard & Jumper wires

### Circuit Wiring
* **Arduino Pin 13** → 220Ω Resistor → LED Anode (+)
* **Arduino GND** → LED Cathode (-)

### How It Works
The script outputs 5V (HIGH) to Pin 13 for 1000ms to illuminate the LED, then drops the pin to 0V (LOW) for 1000ms in an infinite loop.
<img width="2149" height="3383" alt="led-blink" src="https://github.com/user-attachments/assets/8af6cfac-d959-4391-802e-e6a5fb6577dd" />
