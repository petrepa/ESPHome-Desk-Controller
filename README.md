# ESPHome-Desk-Controller
Simple desk controller for controlling volume of a media player and four buttons used for anything
| Front                                                                                  | Top                                                                                | Back                                                                                 |
|----------------------------------------------------------------------------------------|------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------|
| ![Front](https://github.com/petrepa/ESPHome-Desk-Controller/blob/main/media/front.jpg) | ![Top](https://github.com/petrepa/ESPHome-Desk-Controller/blob/main/media/top.jpg) | ![Back](https://github.com/petrepa/ESPHome-Desk-Controller/blob/main/media/back.jpg) |
## Features
* Rotary knob to controll volume of media player
  * Rotary knob can mute or play/pause media player
* Four buttons which can do what ever you want
* Sleek design

# Parts needed
| Part                  | #     | Comment                                    |
|-----------------------|-------|--------------------------------------------|
| Wemos D1 Mini         | 1 pcs | ESP8266 development board                  |
| Rotary encoder module | 1 pcs |                                            |
| Keyboard switches     | 4 pcs | I am using Cherry MX Greens clicky tactile |
| Wires                 | N.A.  |                                            |
| M3 6 mm screw         | 4 pcs |                                            |
| M3 nut                | 4 pcs |                                            |

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
