# ESP8266_BME680_air_quality

![Image](https://github.com/zangaby/ESP8266_BME680_air_quality/blob/main/air_quality_bme680.jpg?raw=true)

Based on https://github.com/3KUdelta/heltec_wifi_kit_32_BME680

Calculates IAQ with a BME680 sensor.

Reading of raw temperature, humidity and gas resistance
Allow offset for temperature calibration
Automatically calculate respective humidity using the August-Roche-Magnus approximation
Calculate IAQ from temperature, humidity and gas resistance following Dr. Julie Riggs, The IAQ Rating Index, www.iaquk.org.uk

Code for those who are interested in using a BME680 sensor via I2C and Adafruit libraries to calculate IAQ without the proprietary libraries from Bosch.

Adafruit´s library: This is a library for the BME280 humidity, temperature & pressure sensor Designed specifically to work with the Adafruit BME280 Breakout ----> http://www.adafruit.com/products/2650 These sensors use I2C or SPI to communicate, 2 or 4 pins are required to interface. The device's I2C address is either 0x76 or 0x77. Adafruit invests time and resources providing this open source code, please support Adafruit andopen-source hardware by purchasing products from Adafruit! Written by Limor Fried & Kevin Townsend for Adafruit Industries. BSD license, all text above must be included in any redistribution

Libraries needed:

ThingPulse SSD1306 (https://github.com/ThingPulse/esp8266-oled-ssd1306)
General Adafruit Sensor (Arduino Library Manager)
Adafruit BME680 (Arduino Library Manager)
SoftwWire Steve Marple (Arduino Library Manager)
AsyncDelay Steve Marple (Arduino Library Manager)

Hardware needed:
bme680 CJMCU
OLED Display (128 x 64)
ESP8266 Wi-Fi Chip (NodeMCU V1)
case: https://www.thingiverse.com/thing:1720314
