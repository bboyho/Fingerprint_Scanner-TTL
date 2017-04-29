Fingerprint_Scanner-TTL
=======================

<table class="table table-hover table-striped table-bordered">
<tr><td><a href="https://www.sparkfun.com/products/11792"><div align="center"><img src="https://cdn.sparkfun.com//assets/parts/8/0/7/3/11792-04a.jpg" title="Fingerprint Scanner - TTL (GT-511C3)
"></div></a></td>
<td><a href="https://www.sparkfun.com/products/13007"><div align="center"><img src="https://cdn.sparkfun.com//assets/parts/9/9/7/2/13007-02.jpg" title="Fingerprint Scanner - TTL (GT-511C1R)"></div></a></td>
<tr><td>Fingerprint Scanner - TTL (GT-511C3) [ SEN-11792 - https://www.sparkfun.com/products/11792 ]</td><td>
Fingerprint Scanner - TTL (GT-511C1R)[ SEN-13007 - https://www.sparkfun.com/products/13007 ]</td></tr>
</table>

This is a great fingerprint module from ADH-Tech that communicates over 3.3V TTL Serial so you can easily embed it into your next project. This repository contains Arduino example code to work with it. This code has been tested with these models:

Repository Contents
-------------------

* **<> Code**

	- **/FPS_GT511C3** - Arduino Library to interface with the sensor.
	- **/FPS_GT511C3/Examples/FPS_Blink** - Blinks the blue LED.
	- **/FPS_GT511C3/Examples/FPS_Enroll** - Enroll a fingerprint.
	- **/FPS_GT511C3/Examples/FPS_IDFinger** - Attempt to identify the fingerprint against the local database.
	- **/FPS_GT511C3/Examples/FPS_Serial_Passthrough** - Basic serial passthrough code that sets up a software serial port to pass data between the Fingerprint Scanner and the SDK Demo Software (SDK_Demo.exe) provided by ADH-Tech.

* **Wiki**

	- [Home](https://github.com/bboyho/Fingerprint_Scanner-TTL/wiki)
	- [Basic Serial UART Hookup](https://github.com/bboyho/Fingerprint_Scanner-TTL/wiki/Basic-Serial-UART-Hookup)
	- [Example Code for Arduino](https://github.com/bboyho/Fingerprint_Scanner-TTL/wiki/Example-Code)
	- [Firmware Overview](https://github.com/bboyho/Fingerprint_Scanner-TTL/wiki/Firmware-Overview)
	- [FPS Experiments](https://github.com/bboyho/Fingerprint_Scanner-TTL/wiki/FPS-Experiments)
	- [Resources and Going Further](https://github.com/bboyho/Fingerprint_Scanner-TTL/wiki/Resources-and-Going-Further)
	- [Tech Support Tips, Troubleshooting & Common Issues](https://github.com/bboyho/Fingerprint_Scanner-TTL/wiki/Tech-Support-Tips,--Troubleshooting,-&--Common-Issues)
	
License Information
-------------------

**Code**

The original library license is as follows:

	"Created by Josh Hawley, July 23rd 2013
	Licensed for non-commercial use, must include this license message
	basically, Feel free to hack away at it, but just give me credit for my work. =)
	TLDR; Wil Wheaton's Law "

**Images**

Images provided in this repository are released under the Creative Commons License [(CC BY-NC-SA 3.0)](https://creativecommons.org/licenses/by-nc-sa/3.0/).

Note: This is a human-readable summary of (and not a substitute for) the [license](https://creativecommons.org/licenses/by-nc-sa/3.0/legalcode).

    You are free to:
    
    - Share — copy and redistribute the material in any medium or format
    
    - Adapt — remix, transform, and build upon the material
    
    The licensor cannot revoke these freedoms as long as you follow the license terms.
    
    You do not have to comply with the license for elements of the material in the public domain or where your use is permitted by an applicable exception or limitation.
    No warranties are given. The license may not give you all of the permissions necessary for your intended use. For example, other rights such as publicity, privacy, or moral rights may limit how you use the material.

