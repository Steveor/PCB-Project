# PCB-Project

Draft KiCAD schematic of a charlieplexed LED array (four 7x7). Based on a working prototype using a SparkFun ESP32 Thing Plus, two Adafruit IS31FL3731 LED drivers, and two 16x9 LED matrices. Ultimately this device captures web traffic and turns on the LEDs based on parsed data. 

Basically I cut and pasted the components from the boards but I am foggy on how the USB to Serial Converter, Voltage Requlator, etc. all fit together. Also not sure of how the VCC, 3.3V, V_USB should be configured. Obviously this throws a ton of errors when I run ERC. 

https://cdn.sparkfun.com/assets/6/d/c/6/c/ESP32_Thing_Plus_Schematic.pdf

https://learn.adafruit.com/assets/30996

https://learn.adafruit.com/assets/30999
