# IoT_IR_Thermometer_v1

IoT IR Thermometer is a DIY device developed to measure surface temperature of an object. It is IoT-enabled device which 
can also publish data over internet to help in generating Heat Map.This device is ESP-12E powered  and houses MLX90614 IR 
Thermometer sensor. The main objective of this DIY is to explore the science and technology behind the Contact-less 
Thermometers and also enable others to develop their own IR Thermometer.

This device is made upto Digital Pre-Fabrication stage which means i have designed the PCB Boards and also 3D encloser 
but yet not fabricated or prototyped it because of non availbility of Resources and facilities due to COVID-19 lockdown.
And it will be great supprt and help if someone having resources and facility would like to fabricate the device.

I am updating the documentation of design and development of IoT_IR_Thermometer_v1 at following link.

https://metastudio.org/t/buidling-of-iot-ir-thermometer-digital-pre-fabrication-stage/3630

The current and also the future development of this work is published under (CC BY-NC-SA 3.0) License. 
One can read more about this license at the link given below.

https://creativecommons.org/licenses/by-nc-sa/3.0/

## Microcontroller used:
I have designed schematic using both Arduino Mini and ESP-12E. But chosen to go for board designing with ESP-12E 
because of integrated Wi-Fi and low power consumption.

## IR Thermometer Sensor selected: 
MLX90614

## For Powering the Device:
In current version_1 I have used 9v Battery which can be replaced whenever required.
Although I wanted to add the rechargeable battery for which there is a requirement for designing Battery Management System (BMS), 
I am working on it and may be come up with it in next development.

## Software Used
All open source software has been used for design this device as follows:

1. Mechanical CAD: FreeCAD
2. Electronic CAD: KiCAD
3. Platform for ESP-12E: Arduino IDE Platform (Programming is still pending, thinking of fabricating the device first, I will publish the  code as soon as i will finish writing it.)

## Device KiCAD Files

Two PCB Boards has been designed, one is User_interface Board accomodating tiny OLED display and five push to ON switches.
The second one is the main board with ESP-12E as the main controller with DS3231 RTC, Trigger Switch, Programming Header, Connector for 
MLX90614 module, Connector for Laser module, Connector for User interface Board.

You can find kiCAD schematic and board files inside the zip folder IoT_IR_Thermometer_v1_PCB Files.zip

## Device FreeCAD Files

You can find STL Files and 3D design source freeCAD files inside the zip folder IoT_IR_Thermometer_v1_3D_Encloser Files.zip

Feel free to ask any query.

### Happy Development !

