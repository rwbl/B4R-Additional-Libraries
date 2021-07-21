# B4R-Additional-Libraries
Open Source Additional Libraries developed for [B4R](https://www.b4x.com/b4r.html) development tool for native Arduino and ESP programs by [Anywhere Software](https://www.b4x.com).

The libraries are 
* developed for personal use only,
* either wrapped from or build upon Open Source Arduino CPP libraries or created new using CPP or B4X language (to create B4XLibs).

## Additional Libraries

* [rBH1750FVI](https://www.b4x.com/android/forum/threads/rbh1750fvi-digital-ambient-light-sensor.75663/) - Get light intensity in Lux from sensor BH1750
* rDHTESP - Get temperature & humidity for DHT11 & DHT22 sensors connected to ESP8266
* rESPOLED1608 - Display text on an OLED display with 16 columns and 8 rows connected to ESP8266
* [rGPRMC](https://www.b4x.com/android/forum/threads/rgprmc.132183/#post-834988) (b4xlib) - Get NMEA RMC Lat / Lon position, Direction Indicator, Speed, Course, Timestamp, Distance Between / Course To for two Lat / Lon positions, Time Difference
* [rLCD1602BigNumbers](https://www.b4x.com/android/forum/threads/rlcd1602bignumbers-display-big-numbers.75745/)- Display BIG NUMBERS on a LCD 16 x 2
* [rLEDController](https://www.b4x.com/android/forum/threads/rledcontroller.132759/) - control up-to 10 LEDs individually, like turn ON/OFF, turn on for period of time or number of timer ticks
* [rLiquidCrystalI2CEx](https://www.b4x.com/android/forum/threads/rliquidcrystali2cex.127742/) - Write to I2C LCD Displays 20x4 or 16x2
* [rMiLYWSD03MMC](https://www.b4x.com/android/forum/threads/rmilywsd03mmc-xiaomi-mi-temperature-humidity-monitor-2.131806/) - Read temperature, humidity and battery values broadcasted via Bluetooth 4.2 BLE by the Xiaomi Mi Temperature and Humidity Monitor 2
* [rMPU6050_I2C](https://www.b4x.com/android/forum/threads/rmpu6050_i2c-motiontracking.76143/)
* [rMultiFuncShield](https://www.b4x.com/android/forum/threads/rmultifuncshield-arduino-multi-function-shield.76003/)
* [rPowerFunctions](https://www.b4x.com/android/forum/threads/lego-power-functions-ir-control.68464/)
* [rTM1637Ex](https://www.b4x.com/android/forum/threads/rtm1637ex.127739/) - Write to TM1637 seven-segment-displays
* rTrafficLight - Controlling 3 LEDs Red-Yellow-Green for learning Arduino Functions but also how to create a B4R library

_Notes_
* B4XLibs are indicated in brackets (b4xlib), all other libraries are CPP libraries.
* Not all libraries are publshed on the B4R Forum.

## Install
### Non B4XLib
From the zip archive, copy the content of the library folder, to the B4R additional libraries folder keeping the folder structure.

**Example Archive rTM1637Ex.zip**
```
<path to b4r additional libraries folder>\rTM1637Ex.xml
<path to b4r additional libraries folder>\rTM1637Ex\rTM1637Ex.h , rTM1637Ex.cpp, TM1637Display.h , TM1637Display.cpp 
```

### B4XLib
From the zip archive, copy the b4xlib file and the xml file to the B4R additional libraries folder.

**Example Archive rGPRMC.zip**
```
<path to b4r additional libraries folder>\rGPRMC.xml
<path to b4r additional libraries folder>\rGPRMC.b4xlib 
```
## Credits
To the developers of the Open Source libraries used and to [Anywhere Software](http://www.b4x.com) for the B4X products.

## Licence
GNU General Public License v3.0.
