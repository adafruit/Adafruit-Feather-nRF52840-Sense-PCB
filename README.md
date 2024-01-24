## Adafruit Feather nRF52840 Sense PCB

<a href="http://www.adafruit.com/products/4516"><img src="assets/4516.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit Feather nRF52840 Sense. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4516

### Description

The Adafruit Feather Bluefruit Sense takes our popular Feather nRF52840 Express and adds a smorgasbord of sensors to make a great wireless sensor platform. This Feather microcontroller comes with Bluetooth Low Energy and native USB support featuring the nRF52840!  This Feather is an 'all-in-one' Arduino-compatible + Bluetooth Low Energy with built in USB plus battery charging. With native USB it works great with CircuitPython, too.

Like the Feather nRF52840, this chip comes with Arduino IDE support - you can program the nRF52840 chip directly to take full advantage of the Cortex-M4 processor, and then calling into the Nordic SoftDevice radio stack when you need to communicate over BLE. Since the underlying API and peripherals are the same for the '832 and '840, you can supercharge your older nRF52832 projects with the same exact code, with a single recompile!

This Feather is also a BLE-friendly CircuitPython board! CircuitPython works best with disk drive access, and this is the only BLE-plus-USB-native chip that has the memory to handle running a little Python interpreter. The massive RAM and speedy Cortex M4F chip make this a good match. Make centrals or peripherals with the ease of CircuitPython.

A chorus of supporting sensors surround the module so you can do all sorts of environmental and motion sensing:

* ST Micro series 9-DoF motion - LSM6DS33 Accel/Gyro + LIS3MDL magnetometer
* APDS9960 Proximity, Light, Color, and Gesture Sensor
* PDM Microphone sound sensor
* SHT Humidity
* BMP280 temperature and barometric pressure/altitude

Features:

* ARM Cortex M4F (with HW floating point acceleration) running at 64MHz
* 1MB flash and 256KB SRAM
* Native Open Source USB stack - pre-programmed with UF2 bootloader
* Bluetooth Low Energy compatible 2.4GHz radio (Details available in the nRF52840 product specification)
* FCC / IC / TELEC certified module
* Up to +8dBm output power
* 21 GPIO, 6 x 12-bit ADC pins, up to 12 PWM outputs (3 PWM modules with 4 outputs each)
* Pin #13 red LED for general purpose blinking, Blue LED for general purpose connection status, NeoPixel for colorful feedback
* Power/enable pin
* Measures 2.0" x 0.9" x 0.28" (51mm x 23mm x 7.2mm) without headers soldered in
* Light as a (large?) feather - 6 grams
* 4 mounting holes
* Reset button
* SWD debug pads on bottom of PCB
* Works out of the box with all of our Adafruit FeatherWings! (Even the UART-using ones like the GPS FeatherWing)

As of January 10, 2024 - We have replaced the discontinued LSM6DS33 with an LSM6DS3TR-C 6 DoF sensor. The performance is improved however new firmware libraries will need to be used in order to read the accelerometer and gyroscope.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
