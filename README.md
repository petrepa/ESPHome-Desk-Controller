# Desk Controller for ESPHome
Simple desk controller for controlling volume of a media player and four buttons used for anything. Powered by ESPHome.
| Front                                                                                  | Top                                                                                | Back                                                                                 |
|----------------------------------------------------------------------------------------|------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------|
| ![Front](https://github.com/petrepa/ESPHome-Desk-Controller/blob/main/media/front.jpg) | ![Top](https://github.com/petrepa/ESPHome-Desk-Controller/blob/main/media/top.jpg) | ![Back](https://github.com/petrepa/ESPHome-Desk-Controller/blob/main/media/back.jpg) |
## Features
* Rotary knob to controll volume of media player
  * Rotary knob can mute or play/pause media player
* Four buttons which can do what ever you want
* Sleek design

# Parts needed
| Part                  | #     | Comment                                        |
|-----------------------|-------|------------------------------------------------|
| Wemos D1 Mini         | 1 pcs | ESP8266 development board                      |
| Rotary encoder module | 1 pcs |                                                |
| Keyboard switches     | 4 pcs | I am using Cherry MX Greens clicky tactile     |
| Key caps              | 4 pcs | I used some spares from a Keychron K2 keyboard |
| Wires                 | N.A.  |                                                |
| M3 6 mm screw         | 4 pcs |                                                |
| M3 nut                | 4 pcs |                                                |

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

![Wiring Diagram](https://github.com/petrepa/ESPHome-Desk-Controller/blob/main/media/wiring_diagram.png)

# How
1. Print the [parts](https://github.com/petrepa/ESPHome-Desk-Controller/tree/main/models). Insert the M3 nuts into the 3D printed lid.
2. Solder components. Do not solder the wires to the keyboard switches before you have intserted the switches into the 3D printed parts. Try to use as short wires as you can to make everything fit in the case
4. Flash Wemos with the [ESPHome code](https://github.com/petrepa/ESPHome-Desk-Controller/blob/main/desk-controller.yaml)
5. Assemble everything. Fasten the rotary knob to the lid. Put a dab of clue on the Wemos ESP8266 chip to fasten it to the case (super glue should do it). Put on the rotary knob and put on your wanted 

## Photos
![Insert nut](https://github.com/petrepa/ESPHome-Desk-Controller/blob/main/media/nut.jpeg)
![Complete wiring](https://github.com/petrepa/ESPHome-Desk-Controller/blob/main/media/wiring.png)
![Wire tucking](https://github.com/petrepa/ESPHome-Desk-Controller/blob/main/media/wire_tucking.png)
![Without knob and caps](https://github.com/petrepa/ESPHome-Desk-Controller/blob/main/media/without_caps.jpg)
