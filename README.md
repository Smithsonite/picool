# **PICOOL**

- [**PICOOL**](#picool)
- [About](#about)
- [Resources/Parts/References](#resourcespartsreferences)
  - [Code](#code)
  - [Hardware](#hardware)
- [Diagram](#diagram)
  - [Breadboard](#breadboard)
  - [Schematics](#schematics)
- [Finished components](#finished-components)
# About
This repository is primarily visuals and references around my modifications to the Raspberry pi 4b official plastic case in tandem with the folks at [Howchoo](https://howchoo.com/g/ote2mjkzzta/control-raspberry-pi-fan-temperature-python). I decided to do this because im building home labs and appliances that will require RPI4's and the fan running constantly will drive me 100% insane.
This will likely be rendered moot after the availability of the [Turing pi 2](https://turingpi.com/) becomes a thing. A proper itx case + 120 or 200MM fan will keep a pi cluster nice and cool!

# Resources/Parts/References

## Code

* [Reference repository](https://github.com/Howchoo/pi-fan-controller)

## Hardware
Below are examples of what I used/ordered to complete this, depending on your case, you may wish to order different sized equipment. You may also be able to get smaller qty of the very specific parts we are going to use. These covered my needs.
* [QuadHands](https://www.amazon.com/gp/product/B00GIKVP5K/ref=ppx_yo_dt_b_asin_title_o00_s01?ie=UTF8&psc=1) - This makes soldering insanely easy.
* Soldering iron - Pick your preference out there. I did this with a $5, 22 year old soldering iron issued from DeVry.
* [Transistor/Resistor kit](https://www.amazon.com/gp/product/B07G46LNCG/ref=ppx_yo_dt_b_asin_title_o05_s01?ie=UTF8&psc=1) - This will contain the parts you need, and many you do not.
* [Jumper Kit](https://www.amazon.com/gp/product/B077N58HFK/ref=ppx_yo_dt_b_asin_title_o05_s01?ie=UTF8&psc=1) - This is highly useful to create a modular product that does not render the fan useless for other projects. 
* [Heat Shrink](https://www.amazon.com/gp/product/B07WWWPR2X/ref=ppx_yo_dt_b_asin_title_o05_s00?ie=UTF8&psc=1) - Good for Tidying up
* [Slide switches](https://www.amazon.com/gp/product/B08232XVL5/ref=ppx_yo_dt_b_asin_title_o02_s00?ie=UTF8&psc=1) - To toggle the software control override
* [Screw kit](https://www.amazon.com/gp/product/B075SBJN6Z/ref=ppx_yo_dt_b_asin_title_o01_s00?ie=UTF8&psc=1) - For mounting the slide switches
* [RPI Case](https://www.canakit.com/raspberry-pi-4-case.html) - This is the case i am modifying to a toggle switch to
* A Dremel or any other tool used to create a slot for the slide switch
* A drill for the switch mounting holes 

# Diagram
These diagrams were created using [Fritzing](https://fritzing.org/) and i highly recommend it for any hobbyists who want a nice looking diagram that will produce Breadboard, Schematic and BCP diagrams simultaneously! Its a steel at $10.

## Breadboard
![Screenshot](Documentation/Images/PiCooler_bb.png)

## Schematics
![Screenshot](Documentation/Images/PiCooler_schem.png)

# Finished components
In order to keep from 