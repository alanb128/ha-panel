# Home Assistant Control Panel
<img src="images/panel1.jpg">
A wall mounted control panel for Home Assistant, as seen in this video: https://youtu.be/Oz87wOJSQm8. 

This repository contains all of the files for the working unit (or will in time - I'm continually adding to this repo.) However, this is not a tutorial or kit - this is mainly a template and provided as inspiration for others wanting to make a similar panel. Feel free to use or modify these files, which are provided as-is and without support. 

## STL Files

The STL files for the five panels are in the STL folder. The sixth panel is the Pi 7" touch screen assembly. I used Inland PLA+ gray filament. See the panel layout image below:

<img src="images/layout_small.jpg">

The frame is called a "[Floater Frame](https://framing4yourself.com/product/matte-black-floater-frame-20101-m/)" and for this project is 9.25 inches x 15.75 inches.

The panels are held in place with a combination of M2.5 and M3 nylon stand offs such as [these](https://www.amazon.com/dp/B073GLW6NL). The M3 stand offs are drectly attached to the holes in the panels, while the M2.5 are used behind the LED seven segment displays to extend them to the back of the frame.

If you want the frame to mount flush to the wall, don't forget to drill extra space for any screw heads on the back of the frame!


## Parts List

For everything except the display:

| Quantity | Part Description | Vendor/link | Notes|
| 1        | M3 Nylon Stand Off Set | [Amazon](https://www.amazon.com/dp/B073GLW6NL) | |
| 1        | 3.3V Buck Regulator | [SparkFun](https://www.sparkfun.com/products/18356) | | 
| 1        | Tactile Push Button Caps, Black | [Amazon](https://www.amazon.com/dp/B07PK3W4XL) | For top display |
| 1        | 2 pack 12x16 Inches Green Translucent Acrylic/Plexiglass Sheet | [Amazon](https://www.amazon.com/dp/B09KC47RLH) | Mounted in back of frame |
| 2        | 10Pcs Non Locking Push Button Switch 19x19mm with LED | [Amazon](https://www.amazon.com/dp/B07CXN14QV) | |

| 1        | Gel filter for 7 segment LEDs | [Amazon](https://www.amazon.com/dp/B0CXXQSDXH) | |
| 30       | 220 ohm 5% resistors | Various | |
| 10       | 1k ohm 5% resistors | Various | | 
| 3        | 3mm Plastic Bevel LED Holder - Pack of 5 | [Adafruit](https://www.adafruit.com/product/2179) | | 
| 1        | Adafruit Perma-Proto 40-Pin Raspberry Pi Half-Size PCB Kit | [Adafruit](https://www.adafruit.com/product/4353)
| 3        | Adafruit MCP23017 I2C GPIO Expander Breakout | [Adafruit](https://www.adafruit.com/product/5346) | | 
| 3        | Adafruit 0.56" 4-Digit 7-Segment Display with I2C Backpack - Red | [Adafruit](https://www.adafruit.com/product/878) | |
| 1        | Key Switch 2PCS 16MM with Key Latching SPDT (2 Position 1NO1NC Round Yellow) | [Amazon](https://www.amazon.com/gp/product/B09FXC26WL) | For safe mode switching | 


