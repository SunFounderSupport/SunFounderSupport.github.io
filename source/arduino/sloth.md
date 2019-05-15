# sloth
![img](../../img/arduino/sloth/sloth.png)

## The servo cannot be rotated

1.Is the connection incorrect? Brown line should be outside

2.Maybe there is no battery or the power switch on the control board is not energized.

3.Check whether the wiring position is correct

4.If there are no problems in the above two steps, please see if the ultrasonic module can be used.

5.If the ultrasonic module can not be used, it may be a problem with the control panel, please contact customer service.
 
6.If one servo is not running, other servos are running normally. Connect the normally rotating steering gear to the interface that does not rotate the steering gear, press the RST key and wait for 5 seconds. If the original normal servo is still running, then it is the servo problem and a replacement servo is needed. If the original normal servo does not rotate, then there is something wrong with the control board, and a control board needs to be replaced.

## The ultrasonic module is not working

1. Maybe there is no battery or the power switch on the control board is not energized.

2. The connection of ultrasonic module may be incorrect.

## Unkonwn board is displayed when the program is downloaded

1. It may be because the pl2303 driver is not installed

## When the servo is calibrated, the servo rotates more than 180 degrees
 Because the servo calibration can adjust the Angle is limited (40 degrees). When there is an exaggerated rotation during the servo calibration, it indicates that the servo test program was not run before assembly.

Remove the abnormal steering gear and retest the servo. After the steering gear turns to 90 degrees, reinstall the servo.

## avrdude: stk500_recv(): programmer is not responding
1. Is the serial port occupied?
2. Usb serial communication is unstable
3. Make sure the board and serial port are selected correctly
4. Maybe your arduino ide version is too high,Select ATmega328P(Old Bootloader) in the processor