SparkFun BNO080 IMU Library
===========================================================

![SparkFun Inertial Measurement Unit - BNO080](https://cdn.sparkfun.com//assets/parts/1/2/7/3/3/14586-VR_IMU__Qwiic__-_BNO080-01.jpg)

[*SparkX IMU BNO080 (SPX-14586)*](https://www.sparkfun.com/products/14586)

The BNO080/BNO085 IMU has a combination triple axis accelerometer/gyro/magnetometer packaged with an ARM Cortex M0+ running powerful algorithms. This enables the BNO080 Inertial Measurement Unit (IMU) to produce accurate rotation vector headings with an error of 5 degrees or less. It's what we've been waiting for: all the sensor data is combined into meaningful, accurate IMU information.

This IC was designed to be implemented in Android based cellular phones to handle all the computations necessary for virtual reality goggles using only your phone. The sensor is quite powerful but with power comes a complex interface. We've written an I<sup>2</sup>C based library that provides the rotation vector (the reading most folks want from an IMU) as well as raw acceleration, gyro, and magnetometer readings. The sensor is capable of communicating over SPI and UART as well!

In addition the BNO080 IMU provides a built-in step counter, tap detector, activity classifier (are you running, walking, or sitting still?), and a shake detector. We are duly impressed.

Library written by Nathan Seidle ([SparkFun](http://www.sparkfun.com)).

Repository Contents
-------------------

* **/examples** - Example sketches for the library (.ino). Run these from the Arduino IDE. 
* **/src** - Source files for the library (.cpp, .h).
* **keywords.txt** - Keywords from this library that will be highlighted in the Arduino IDE. 
* **library.properties** - General library properties for the Arduino package manager. 

Documentation
--------------

* **[Installing an Arduino Library Guide](https://learn.sparkfun.com/tutorials/installing-an-arduino-library)** - Basic information on how to install an Arduino library.
* **[Product Repository](https://github.com/sparkfunX/Qwiic_IMU_BNO080)** - Main repository (including hardware files)

License Information
-------------------

This product is _**open source**_! 

Various bits of the code have different licenses applied. Anything SparkFun wrote is beerware; if you see me (or any other SparkFun employee) at the local, and you've found our code helpful, please buy us a round! Anything Maxim wrote has its own license. Anything that was co-writing with Peter Jansen is BSD.

Please use, reuse, and modify these files as you see fit. Please maintain attribution to SparkFun Electronics and release anything derivative under the same license.

Distributed as-is; no warranty is given.

- Your friends at SparkFun.
