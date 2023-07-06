# lgpio-BlinkLED
Beginning project with lgpio library for the Raspberry Pi to blink an LED light

This example uses the latest and most compatible library for the Raspberry Pi in Xojo 2023 r1.1. The Xojo library can be downloaded for free at: https://github.com/eugenedakin/lgpio-GPIO. This is a lgpio local library that is a replacement for the deprecated sysfs library that
is to be used with Xojo apps. This library uses local c language calls, which means updates should be minimal and your code should be stable for a very long time. 

![](https://github.com/eugenedakin/lgpio-BlinkLED/blob/main/BlinkSmall.png)

Below is the schematic for this example project.

![](https://github.com/eugenedakin/lgpio-BlinkLED/blob/main/HelloWorldSchematic.png)

The lgpio library can be installed Raspberry Pi OS (6 July 2023) and instructions 
are available at http://abyz.me.uk/lg/download.html

Install instructions are:
1) sudo apt install swig python-dev python3-dev
2) sudo apt install python-setuptools python3-setuptools
3) wget http://abyz.me.uk/lg/lg.zip
4) unzip lg.zip
5) cd lg
6) make
7) sudo make install
8) create a Blink example program and copy the program and libraries to the RaspberryPi Desktop
9) give the executable permission to run with something like: 'sudo chmod +x Blink'
10) run the program with something like: 'sudo ./Blink'

This example project uses the lgpio libray and executes a blinking LED program through the input/output electronic pin ports on the Raspberry Pi.
