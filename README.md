## Installation of Arduino IDE


Arudino is an open-souce platform that is commonly used to program microcontrollers.

## More information about Arduion can be found at

-https://www.arduino.cc/


## How to Install

The Arduino IDE can be dowloaded for free at https://www.arduino.cc/en/software

## Hardware 
- Arduino Uno or similar board
-One LED
-330 Ohm Resistor
-(Optional Wire to Connect)

## Basic Project
After installation, a new file should appear. You window should appear as:

<p align="left">
        <img src="C:\Users\rasha\OneDrive\Documents\GitHub\Installation-of-Arduino-IDE\basic_view.png" width="50%">
/>
</p>

Ensure that you've selected the correct port and board:

<p align="left">
        <img src="C:\Users\rasha\OneDrive\Documents\GitHub\Installation-of-Arduino-IDE\tools.png" width="50%">
/>
</p>

# Schematic

<p align="left">
        <img src="C:\Users\rasha\OneDrive\Documents\GitHub\Installation-of-Arduino-IDE\circuit.png" width="50%">
/>
</p>

# Code

```cpp
void setup() {
  // put your setup code here, to run once:
  LED = 13;
  pinMode(LED, OUTPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
  digitalWrite(LED, HIGH); // Turn LED on
  delay(2000};             // Wait 2 seconds
  digitalWrite(LED, LOW);  // Turn LED off
  delay(1000);             // Wait 1 second
}

## Contributions
Documentation - Isaiah Overton, Southern Illinois University - Carbondale
Sources - www.arduino.cc
 Format - https://www.makeareadme.com/

## License
[MIT](https://choosealicense.com/licenses/mit/)