# PiCar-S

![img](../../img\raspoberrypi\picar-s\sunfounder_picar-s_kit_01.jpg)

## The connection error is because the car and client do not have the correct network connection, you can try the following:

1. Check if the server side on the Raspberry Pi is open correctly and there is no error message.
2. Confirm that your client and Raspberry Pi are on the same network.

## Connection to pi connection via SSH failed

Please create a new empty file called ssh in the /boot directory, delete the file suffix name, this file is used to enable raspberry Pi remote login

## How to adjustment the turning angle when the car runs the line_follower?

In line 29 of the line_follower.py file, modifying the value of this parameter can challenge the turning angle.
![img](../../img\raspoberrypi\picar-s\modifyTurningAngle.png)
The turning angle is up to 45 degrees, otherwise the servo may be damaged.