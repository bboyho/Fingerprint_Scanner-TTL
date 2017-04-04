Fingerprint_Scanner-TTL
=======================

[![FingerPrint Scanner](https://dlnmh9ip6v2uc.cloudfront.net/images/products/1/1/7/9/2/11792-01_medium.jpg)  
*Fingerprint Scanner - TTL*](https://www.sparkfun.com/products/11792)

This is a great fingerprint module from ADH-Tech that communicates over 3.3V TTL Serial so you can easily embed it into your next project. This repository contains Arduino example code to work with it. This code has been tested with these models:
 
Fingerprint Scanner - TTL (GT-511C3)(SEN-11792) [ [https://www.sparkfun.com/products/11792](https://www.sparkfun.com/products/11792) ]

Fingerprint Scanner - TTL (GT-511C1R)(SEN-13007) [ [https://www.sparkfun.com/products/13007](https://www.sparkfun.com/products/13007) ]

Repository Contents
-------------------
*  **/Documentation/README.md** - Documentation for the FPS including a basic serial UART hookup and how to use it with Hawley's FPS_GT511C3 library.
*  **/FPS_GT511C3** - Arduino Library to interface with the sensor.
*  **/FPS_GT511C3/Examples/FPS_Blink** - Blinks FPS blue LED.
*  **/FPS_GT511C3/Examples/FPS_Enroll** - Enroll fingerprint using FPS.
*  **/FPS_GT511C3/Examples/FPS_IDFinger** - Attempt to identify previously enrolled fingerprint saved in its database.
*  **/FPS_GT511C3/Examples/FPS_Serial_Passthrough** - Basic serial passthrough code that sets up a software serial port to pass data between the Fingerprint Scanner and the SDK Demo Software (SDK_Demo.exe) provided by ADH-Tech.

License Information
-------------------

The original library license is as follows:

"	Created by Josh Hawley, July 23rd 2013
	Licensed for non-commercial use, must include this license message
	basically, Feel free to hack away at it, but just give me credit for my work. =)
	TLDR; Wil Wheaton's Law "
