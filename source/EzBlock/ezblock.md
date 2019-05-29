# EzBlock

![img](../../img\ezblock\ezblock.jpg)

## What version of the Raspberry Pi does this support i.e. 3B, 3B+?? 

Ezblock Pi is build for Pi 3B+. As Raspberry Pi is highly compatible with each others, all the same form of Raspberry Pi is considered compatible. We will test all of them later.

## What happens to the pins on the Pi, Do you provide access to all of the pins or only provide access to a subset of the pins? 

Ezblock Pi have 2x20 pinout. With the on-board 8-channel PWM output, 8-channel 12-bit ADC input, and 8 power pin, it only left another 16-pin for Raspberry Pi, 10 GPIOs, 1 set of SPI(with CE0) and 1 set of I2C. We use almost all other GPIOs for the onboard LED, reset button, bluetooth, etc.

## Details about the programming software is VERY IMPORTANT. Links to documentation or additional close up videos would help. 

The close up video video will be out soon.

##  Support for other sensors, etc. How easy is it to add existing off the shelf sensors and create projects. A lot of us have tons of sensors, actuators lying around the house. 

Currently Ezblock Studio only supports all the sensors and actuators  of the sensor kits, which you can drag out from the hardware simulator, and corresponding blog creates. For other blocks, you can directly control the sensors with the Pin control block or I2C, SPI clock. In the future, you can write your own libraries, or download others sensor libraries to control the sensors.

## Does this need a special Raspberry Pi Case?

No, you just need the Ezblock Pi HAT. The case is just a protection.