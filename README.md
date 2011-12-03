ATtiny 44/84 and 45/85 Programmer
=================================
Copyright 2011 Design Tech Industries (DTI)

DTI email: <jameskun89@rocketmail.com>

The **ATtiny 44/84 and 45/85 Programmer** is the continuation of a project I started one Saturday afternoon, that being the ATtiny Programmer Shield
(https://github.com/punklibrarian/ATtiny_45_and_85_programmer_shield). It uses an ATMega328 running the Arduino boot loader and the ArduinoISP sketch to 
program ATtiny 44/84 and 45/85 micro controllers. It uses what I learnt from reading the tutorials at High-Low Tech on programming ATtiny's using an Arduino
(http://hlt.media.mit.edu/?p=1229 http://hlt.media.mit.edu/?p=1695).

Features:

 * Activity LEDs
 * ATtiny 45/85 Pin 0 LED (for Blink sketch test) 
 * ATtiny 44/84 Pin 6 LED (for Blink sketch test)
 * ATMega328 Pin 13 LED (for Blink sketch test)
 * A 10uF capacitor between RST and GND to stop Arduino auto-resetting. 
 * Open Source; OSHW compliant
 * Design files freely available

In this repository you will find the gerber files for BatchPCB (http://batchpcb.com), along with project (.pro), board (.brd) 
and schematic (.sch) files for this shield in the 'EAGLE and 'KiCad' folders. 

INSTALLATION
------------
**EAGLE**
The design is saved as an EAGLE project. EAGLE PCB design software is available from www.cadsoftusa.com 
free for non-commercial use and can be installed on Windows and Mac, with Linux support through WINE. 
To use this project download it and place the directory containing these files into the "eagle" directory 
on your computer. Then open EAGLE and navigate to Projects -> eagle -> ATtiny_4585_and_4484_programmer.

**KiCad**
KiCad EDA Suite is an Open Source alternative to EAGLE. It is available on Windows and Linux and can be installed 
on Mac. It is available from http://kicad.sourceforge.net and works in a similar way to EAGLE. You will find project 
files for KiCad in the aptly named folder in this repository. To use this project download it and place the directory 
containing these files into a folder of your choice. Then open KiCad and navigate to File -> Open -> 
'FOLDER_OF_YOUR_CHOICE' -> ATtiny_4585_and_4484_programmer.pro

HOW TO USE
----------
Follow instructions outlined in this section at the ATtiny 45 and 85 Programmer Shield (https://github.com/punklibrarian/ATtiny_45_and_85_programmer_shield).

DISTRIBUTION
------------
The specific terms of distribution of this project are governed by the license referenced below.

LICENSE
-------
> This work is licensed under the Creative Commons Attribution-ShareAlike License.  
> 
> To view a copy of this license, visit:
> 
>   http://creativecommons.org/licenses/by-sa/3.0/  
>   http://creativecommons.org/licenses/by-sa/3.0/legalcode
> 
> or send a letter to
> 
>   Creative Commons  
>   171 Second Street, Suite 300  
>   San Francisco  
>   California, 94105  
>   USA

The "license" folder within this repository also contains copies of the
license(s) referenced above.