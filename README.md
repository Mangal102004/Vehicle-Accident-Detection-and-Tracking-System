# Vehicle-Accident-Detection-and-Tracking-System
Embedded system project on Vehicle Accident Detection and Tracking using Tiva TM4C123GXL

This repository aims at building an embedded system that can be installed in a vehicle , through which when an accident is detected, sends an alert message to a registered mobile number along with the google maps link of the accident location. 

# Hardware used :
  1)TIVA TM4C123GXL
  <br>2)Vibration sesnor (SW420)
  3)GSM module (SIM900A)
  4)GPS module (U-Blox NEO-6M)

# Software used :
  1)Code Composer Studio (Version 12.7.1)
  2)TivaWare (SW - TM4C software development kit)
  3)Stellaris ICDI 

# Pin Configurations:
  1)Vibration Sensor : VCC=>3.3V , GND=>GND , D0=>PF4
  2)GSM module : VCC=>5V , TX=>PB0 (UART1 RX) , RX=>PB1 (UART1 TX) , GND=>GND
  3)GPS module : VCC=>5V , TX=>PE4 (UART5 RX) , RX=>PE5 (UART5 TX) , GND=>GND
  
 
