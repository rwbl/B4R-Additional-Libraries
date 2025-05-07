# B4R-Additional-Libraries
Open Source Additional Libraries developed for [B4R](https://www.b4x.com/b4r.html) development tool for native Arduino and ESP programs by [Anywhere Software](https://www.b4x.com).

The libraries are 
* developed for personal use only,
* either wrapped from or build upon Open Source Arduino CPP libraries or created new using CPP or B4X language (to create B4XLibs).

## Additional Libraries

* [rBH1750FVI](https://www.b4x.com/android/forum/threads/rbh1750fvi-digital-ambient-light-sensor.75663/) - Get light intensity in Lux from sensor BH1750.
* [rBLEBeacon-091](https://www.b4x.com/android/forum/threads/rblebeacon-esp32.165566/) - create a Bluetooth Low Energy (BLE) Beacon using the ESP32 BLE feature.
* [rBLEServer-089](https://www.b4x.com/android/forum/threads/rbleserver-esp32.165435/) - create a Bluetooth Low Energy (BLE) server.
* rDHTESP - Get temperature & humidity from DHT11 & DHT22 modules connected to ESP8266.
* rDHTEx - Get temperature & humidity from DHT11 & DHT22 modules.
* rESPOLED1608 - Display text on an OLED display with 16 columns and 8 rows connected to an ESP8266.
* [rESP3228CYD-060](https://www.b4x.com/android/forum/threads/resp3228cyd.166140/) - SPI LCD graphics library with basic functionality for the Sunton ESP32 2.8" TFT Cheap Yellow Display (CYD).
* [rESP32Watchdog-100](https://www.b4x.com/android/forum/threads/resp32watchdog.166707/) - ESP32 hardware watchdog.
* [rGPRMC](https://www.b4x.com/android/forum/threads/rgprmc.132183/#post-834988) (b4xlib) - Get NMEA RMC Lat / Lon position, Direction Indicator, Speed, Course, Timestamp, Distance Between / Course To for two Lat / Lon positions, Time Difference.
* [rHCSR04](https://www.b4x.com/android/forum/threads/rhcsr04-ultrasonic-distance-sensor.132953/#post-839833) - Read the distance from an Ultrasonic Distance Sensor HC-SR04.
* [rIRRemoteEx-080](https://www.b4x.com/android/forum/threads/rirremoteex.166899/) - Sending & receiving of infra-red (IR) signals.
* [rLCD1602BigNumbers](https://www.b4x.com/android/forum/threads/rlcd1602bignumbers-display-big-numbers.75745/)- Display BIG NUMBERS on a LCD 16 x 2.
* [rLEDController](https://www.b4x.com/android/forum/threads/rledcontroller.132759/) (b4xlib) - Control up-to 10 LEDs individually, like turn ON/OFF, turn on for period of time or number of timer ticks.
* [rLegoinoBoost](https://www.b4x.com/android/forum/threads/rlegoinoboost.135237/) - Control via an ESP32 the LEGO® Motorized Hub from the [LEGO BOOST Creative Toolbox 17101](https://www.lego.com/en-de/product/boost-creative-toolbox-17101).
* [rLiquidCrystalI2CEx](https://www.b4x.com/android/forum/threads/rliquidcrystali2cex.127742/) - Write to I2C LCD Displays 20x4 or 16x2.
* rMAX6675 - Thermosensor MAX6675 connected to Arduino or ESP8266.
* [rLovyanGFXEx-100](https://www.b4x.com/android/forum/threads/rlovyangfxex-esp32.166606/) - SPI LCD graphics library for selected displays controlled by an ESP32.
* [rMiLYWSD03MMC](https://www.b4x.com/android/forum/threads/rmilywsd03mmc-xiaomi-mi-temperature-humidity-monitor-2.131806/) - Read temperature, humidity and battery values broadcasted via Bluetooth 4.2 BLE by the Xiaomi Mi Temperature and Humidity Monitor 2.
* [rMPU6050_I2C](https://www.b4x.com/android/forum/threads/rmpu6050_i2c-motiontracking.76143/) - Motion Tracking.
* [rMultiFuncShield](https://www.b4x.com/android/forum/threads/rmultifuncshield-arduino-multi-function-shield.76003/).
* [rPowerFunctions](https://www.b4x.com/android/forum/threads/lego-power-functions-ir-control.68464/) - Control LEGO Power Functions via IR transmitter.
* [rRFXMeter](https://www.b4x.com/android/forum/threads/rrfxmeter.139786/#post-885187) (b4xlib) - Send sensor & actuator data from an [Arduino](https://www.arduino.cc/) Microcontroller to [Domoticz Home Automation System](https://domoticz.com/) by using a [RFXCOM RFXtrx433e](http://www.rfxcom.com/RFXtrx433E-USB-43392MHz-Transceiver/en) transceiver.
* [rTM1637Ex](https://www.b4x.com/android/forum/threads/rtm1637ex.127739/) - Interfacing the TM1637 4-Digit 7-segment-display.
* rTrafficLight - Controlling 3 LEDs Red-Yellow-Green for learning Arduino Functions but also how to create a B4R library.

_Notes_
* B4XLibs are indicated in brackets (b4xlib), all other libraries are CPP libraries (compiled with the Arduino CLI).
* Not all libraries are published on the [B4R Forum](https://www.b4x.com/android/forum/#b4r-arduino-esp8266-and-esp32.74) / [B4R Libraries](https://www.b4x.com/android/forum/forums/b4r-libraries.78/).
* Checkout for updates or additionla information on the library link provided.
* LEGO® is a trademark of the LEGO Group of companies.

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
_Note:_ rGPRMC.xml is optional.

## Credits
* To the developers of the various Open Source libraries used / wrapped for the B4R libraries/programs.
* To [Anywhere Software](http://www.b4x.com) for the B4X products.

## Licence
GNU General Public License v3.0. 
Developed for personal use only.
