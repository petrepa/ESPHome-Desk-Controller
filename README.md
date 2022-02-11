# ESPHome-Desk-Controller
Simple desk controller for controlling volume of a media player and four buttons used for anything

## Features
* Rotary knob to controll volume of media player
  * Rotary knob can mute or play/pause media player
* Four buttons which can do what ever you want
* Sleek design

# Parts needed
| Part                  | Comment                                    |
|-----------------------|--------------------------------------------|
| Wemos D1 Mini         | ESP8266 development board                  |
| Rotary encoder module |                                            |
| Keyboard switches     | I am using Cherry MX Greens clicky tactile |
| Wires                 |                                            |

## Pinout
| Wemos D1 Mini | Rotary Encoder | Buttons        | Cable color |
|---------------|----------------|----------------|-------------|
| 3V3           | VCC            |                | Red         |
| GND           | GND            | Button 1/2/3/4 | Black       |
| D1            |                | Button 1       | Yellow      |
| D2            |                | Button 2       | Purple      |
| D3            |                | Button 3       | Blue        |
| D4            |                | Button 4       | Green       |
| D5            | PIN A (CLK)    |                | Yellow      |
| D6            | Button (SW)    |                | Green       |
| D7            | PIN B (DT)     |                | Blue        |

# How
1. Print the parts
2. Solder components
4. Flash Wemos
5. Assemble

# Assemble

![nut](https://github.com/petrepa/ESPHome-Desk-Controller/blob/main/media/nut.jpeg)
