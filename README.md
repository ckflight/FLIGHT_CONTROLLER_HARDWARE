# FLIGHT_CONTROLLER_HARDWARE

This is the first Flight_Controller Board i designed a few years ago with ATMEL SAM3X8E MCU, BNO055 Orientation Sensor, TPA2012D Audio Amplifier, CC2541 Bluetooth IC, 4 channel PWM input for radio interface (no SBUS input is available on this version), Microcard slot for data logging and ESC PWM pins. Board is tested on a Quadcopter and it is working fine.

CC2541 IC can be flashed with HM10 firmware for the simplicity if you do not want to implement your own 8051 code in it.

It can be used with Arduino IDE for simple test and implementation.

50 Ohm impedance microstrip transmission line is making 0.342mm trace width with below stackup.

2 x 1W Stereo Speaker can be connected to the Audio Amplifier.

Since this was my first flight controller board design, i did not added a good stand alone gyro sensor. Instead used BNO055 since it provides both Euler Angle and Gyro Acc and Magnetometer results.

Stackup layer information can be found here: https://docs.oshpark.com/services/four-layer/

![IMG_20200227_003748](https://user-images.githubusercontent.com/61315249/75391439-1f192a80-58fb-11ea-89f6-d79ffdd6ec90.jpg)

![flight controller](https://user-images.githubusercontent.com/61315249/82239704-dbeeb680-9941-11ea-99d1-bf97cf3a3f58.png)
