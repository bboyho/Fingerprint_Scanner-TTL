Fingerprint_Scanner-TTL
=======================

[![FingerPrint Scanner](https://dlnmh9ip6v2uc.cloudfront.net/images/products/1/1/7/9/2/11792-01_medium.jpg)  
*Fingerprint Scanner - TTL*](https://www.sparkfun.com/products/11792)

This is a great fingerprint module from ADH-Tech that communicates over 3.3V TTL Serial so you can easily embed it into your next project. This repository contains Arduino example code to work with it. This code has been tested with these models:
 
Fingerprint Scanner - TTL (GT-511C3)(SEN-11792) [ [https://www.sparkfun.com/products/11792](https://www.sparkfun.com/products/11792) ]

Fingerprint Scanner - TTL (GT-511C1R)(SEN-13007) [ [https://www.sparkfun.com/products/13007](https://www.sparkfun.com/products/13007) ]

Repository Contents
-------------------

* **<> Code**

	- **/FPS_GT511C3** - Arduino Library to interface with the sensor.
	- **/FPS_GT511C3/Examples/FPS_Blink** - Blinks FPS blue LED.
	- **/FPS_GT511C3/Examples/FPS_Enroll** - Enroll fingerprint using FPS.
	- **/FPS_GT511C3/Examples/FPS_IDFinger** - Attempt to identify previously enrolled fingerprint saved in its database.
	- **/FPS_GT511C3/Examples/FPS_Serial_Passthrough** - Basic serial passthrough code that sets up a software serial port to pass data between the Fingerprint Scanner and the SDK Demo Software (SDK_Demo.exe) provided by ADH-Tech.

* **Wiki**

	- [Home](https://github.com/bboyho/Fingerprint_Scanner-TTL/wiki) - Includes suggested readings before getting started with the FPS.
	- [Basic Serial UART Hookup](https://github.com/bboyho/Fingerprint_Scanner-TTL/wiki/Basic-Serial-UART-Hookup) - Basic FPS pinout and how to connect to it using an FTDI. 
	- [Example Code](https://github.com/bboyho/Fingerprint_Scanner-TTL/wiki/Example-Code) - Explanation the Arduino example code and how to connect using a 5V Arduino microcontroller.
	- [Firmware Overview](https://github.com/bboyho/Fingerprint_Scanner-TTL/wiki/Firmware-Overview) - Explanation of what you will see when using the FPS_GT511C3 library on an Arduino. 
	- [Resources and Going Further](https://github.com/bboyho/Fingerprint_Scanner-TTL/wiki/Resources-and-Going-Further) - Additional tutorials and example projects.
	- [Tech Support Tips, Troubleshooting & Common Issues](https://github.com/bboyho/Fingerprint_Scanner-TTL/wiki/Tech-Support-Tips,--Troubleshooting,-&--Common-Issues) - Common issues that you might run into and methods to troubleshoot.
License Information
-------------------

The original library license is as follows:

"	Created by Josh Hawley, July 23rd 2013
	Licensed for non-commercial use, must include this license message
	basically, Feel free to hack away at it, but just give me credit for my work. =)
	TLDR; Wil Wheaton's Law "
