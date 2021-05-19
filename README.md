# Game of Life on the Raspberry Pi Pico with OLED screen
MicroPython script to run Game of Life on the Raspberry Pi Pico with 128 px x 64 px OLED screen.

![Project image](img/project_img.jpg?raw=true)

## Detailed description
Schematic 
| Pico  | SSD1306 |
| ------------- | ------------- |
| GND  | GND  |
| 3v3(OUT)  | VCC  |
| GP1  | SCL  |
| GP0  | SDA  |

## Dependencies
You need one library to run this script:

[SSD1306](https://github.com/adafruit/Adafruit_Python_SSD1306/blob/master/Adafruit_SSD1306/SSD1306.py)
