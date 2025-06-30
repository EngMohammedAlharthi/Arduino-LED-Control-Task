# Arduino LEDs and Buttons Control

This project demonstrates a simple Arduino circuit that controls 3 LEDs using 3 push buttons.

Components Used:
- Arduino Uno R3  
- 3x LEDs (Red)  
- 3x 220Ω resistors  
- 3x Push buttons  
- Breadboard & jumper wires  

Functionality:
Each button is connected to a digital input pin and mapped to an individual LED.  
When a button is pressed, the corresponding LED turns on. Once released, the LED turns off.

Pins Mapping:
- Button 1 → Pin 2 → LED 1 → Pin 12  
- Button 2 → Pin 3 → LED 2 → Pin 11  
- Button 3 → Pin 4 → LED 3 → Pin 13 (built-in)

Notes:
- Buttons are connected with pull-down configuration.
- The project is simulated and tested in Tinkercad.
