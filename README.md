# Components
## Temperature sensors:
### Types of temperature sensors:
* [Thermocouples](https://en.wikipedia.org/wiki/Thermocouple)
* [Resistance temperature detectors (RTD)](https://en.wikipedia.org/wiki/Resistance_thermometer)
* [Thermistors](https://en.wikipedia.org/wiki/Thermistor)
* [Semiconductors based integrated circuits]()

| Sensor        | Sensor type   | Interface  | Range     | Resolution | Price    | Supply Voltage Range   | Library | Datasheet | Notes |
| :-----------: | :----------:  | :-------:  | :-------: | :--------: | :------: | :-------------------:  | :--------------: | :-----------:|:-----------:|
| MAX31855      | Thermocouple  |    SPI     | Depends on the type | 14-Bit;0.25°C |12.60 €|3.0V< VCC< 3.6V |[Library](https://github.com/Tuckie/max31855) | [Datasheet](https://bit.ly/366CidX)  | |
| MCC134        | Thermocouple  | general purpose I/O (GPIO) | Depends on the type | ADC resolution: 24 bits |137.00 € | 3.3 V | [Library](https://github.com/mccdaq/daqhats) |[Datasheet](https://www.mccdaq.com/PDFs/specs/DS-MCC-134.pdf)  | up to 4 thermo couples|
|DFR0558  | Thermocouple K Type |  I²C |   -270°C~1372°C   | 14 bit  |  €20.93  | 3.3V and 5V |[Library](https://github.com/DFRobot/DFRobot_MAX31855)|[Datasheet](https://media.digikey.com/pdf/Data%20Sheets/DFRobot%20PDFs/DFR0558_Web.pdf)| Probe can be attached |
| ADS1118 |Thermocouple K-Type|SPI|  –200°C to +1250°C  |16bit; 0.03125°C|111.52 €| 2v~7v |[Library](https://github.com/jonathanimb/ADS1118)|[Datasheet](https://www.ti.com/lit/ds/symlink/ads1118.pdf)| Ultrasmall, low power consumption |
|MCP9600|Thermocouple|I²C|Depends on the type|0.0625°C|5.97€|2.7v~5.5v|[Library](https://github.com/pimoroni/mcp9600-python)|[Datasheet](https://ww1.microchip.com/downloads/en/DeviceDoc/MCP960X-Data-Sheet-20005426.pdf)|  |
|MAX31850K| Thermocouple | 1-Wire|Depends on the type |14bit;0.25°C|21.79€ |3.3V |[Library](https://github.com/Seeed-Studio/Seeed_MAX31850K)|[Datasheet](https://cdn-shop.adafruit.com/datasheets/MAX31850-MAX31851.pdf)|  |
|AD8495|Thermocouple K-type| Analog  |−25°C to +400°C|  | 13.28 € |3.3V and 5V|[Library](https://github.com/adafruit/Adafruit-AD8495-Breakout-PCB)|[Datasheet](https://www.analog.com/media/en/technical-documentation/data-sheets/ad8494_8495_8496_8497.pdf)    | [Accessories](https://www.adafruit.com/product/270)|
|DS18B20|Thermistor|1-Wire|-55°C to +125°C|Programmable Resolution from 9 Bits to 12 Bits| 2.8 € |3v~5v|[Library](https://github.com/victorjonsson/raspberry-pi-temp-sensors)|[Datasheet](https://datasheets.maximintegrated.com/en/ds/DS18B20.pdf)|  |
|MAX31865|RTD | SPI | -200°C to +800°C | 0.03125°C  |4.32 €| 3.3v |[Library](https://circuitpython.readthedocs.io/projects/max31865/en/latest/) |[Datasheet](https://datasheets.maximintegrated.com/en/ds/MAX31865.pdf)|[Accessories](https://www.adafruit.com/product/3290)|
|MAX31875|IC | I²C & SMBus | -40°C to +145°C | up to 0.0625°C| 7.56€| 3.3V |[Library]()  |[Datasheet](https://datasheets.maximintegrated.com/en/ds/MAX31875.pdf)| |
|TMP117 |IC | I²C| |16-bit/0,0078°C |–55 °C to 150 °C | 3.3V or 5v| 13,64 € |[Datasheet](https://www.ti.com/lit/ds/symlink/tmp117.pdf?ts=1625171110618&ref_url=https%253A%252F%252Fwww.ti.com%252Fproduct%252FTMP117) | |

## Humidity+ temperature
| Sensor        | Sensor type   | Interface  | Range     | Resolution | Price    | Supply Voltage Range   | Library | Datasheet | Notes |
| :-----------: | :----------:  | :-------:  | :-------: | :--------: | :------: | :-------------------:  | :--------------: | :-----------:|:-----------:|
| AHT20||I²C|Temp: -40°C to 85°C, Humidity: 0~100%|Humidity: 0.024%, Temp: 0.01°C|5,34 €|3.3V or 5V|[Library](https://github.com/adafruit/Adafruit_CircuitPython_AHTx0)|[Datasheet](https://files.seeedstudio.com/wiki/Grove-AHT20_I2C_Industrial_Grade_Temperature_and_Humidity_Sensor/AHT20-datasheet-2020-4-16.pdf)|
| HTU21D-F | |I²C | Temp: -30~90°C, Humidity: 5% to 95% RH| 8-12 bits|16,45 €|3.3V|[Library](https://github.com/bbx10/htu21dflib)|[Datasheet](https://cdn-shop.adafruit.com/datasheets/1899_HTU21D.pdf) | |
|DHT22 | |1-Wire |humidity 0-100%RH; temperature -40~80Celsius|humidity 0.1%RH; temperature 0.1°C | 6.56€ |3.3-6V | [Library](https://github.com/adafruit/Adafruit_Python_DHT)| [Datasheet](https://www.sparkfun.com/datasheets/Sensors/Temperature/DHT22.pdf)|   

## Pressure 
| Sensor        | Sensor type   | Interface  | Range     | Resolution | Price    | Supply Voltage Range   | Library | Datasheet | Notes |
| :-----------: | :----------:  | :-------:  | :-------: | :--------: | :------: | :-------------------:  | :--------------: | :-----------:|:-----------:|
| BME680| air quality| I²C and SPI| P: 300 to 1100hpa, H: 0 to 100%, T: -40°C to 85°C| | 25.2€ | 3.3V|[Library](https://github.com/pimoroni/bme680-python) |[Datasheet](https://cdn-shop.adafruit.com/product-files/3660/BME680.pdf) |Low power gas, pressure, temperature & humidity sensor |
|LPS22|absolute digital output barometer | I²C and SPI |260-1260 hPa |24-bit pressure data and 16-bit temperature data | 6,15 € | 3.3V |[Library](https://learn.adafruit.com/adafruit-lps25-pressure-sensor/python-circuitpython) |[Datasheet](https://www.st.com/resource/en/datasheet/dm00140895.pdf)|pressure & temperature sensor | 
|BMP085 | |I²C |300 to 1100hPa | P:0.01hPa, T:0.1°C || 3.3V |[Library](https://learn.adafruit.com/using-the-bmp085-with-raspberry-pi/using-the-adafruit-bmp-python-library) |[Datasheet](https://cdn-shop.adafruit.com/datasheets/BMP085_DataSheet_Rev.1.0_01July2008.pdf) | | 
## CO₂
| Sensor        | Sensor type   | Interface  | Range     | Resolution | Price    | Supply Voltage Range   | Library | Datasheet | Notes |
| :-----------: | :----------:  | :-------:  | :-------: | :--------: | :------: | :-------------------:  | :--------------: | :-----------:|:-----------:|
|SCD30 Sensor module| NDIR|UART or I²C |400 ppm – 10.000 ppm | 30ppm| 46.29 €| 3.3V – 5.5V|[Library](https://pypi.org/project/scd30-i2c/)|[Datasheet](https://www.mouser.com/datasheet/2/813/Sensirion_CO2_Sensors_SCD30_Preliminary-Datasheet-1516638.pdf) |Co2, Temperature and Humidity are included. Operating range for co2 sensor : 0 – 50°C|
| Senseair S8 LP |NDIR |UART |400–2000ppm |40ppm |36.00 €|5V |[Library](http://co2meters.com/Documentation/AppNotes/AN168-S8-raspberry-pi-uart.pdf) |[Datasheet](https://rmtplusstoragesenseair.blob.core.windows.net/docs/Dev/publicerat/PSH1944.pdf) [Datasheet2](http://www.co2meters.com/Documentation/Datasheets/DS-S8-3.2.pdf) |[Accessories](https://senseair.com/products/accessories/sadk-senseair-development-kit/)|
|MH-Z19C |NDIR |UART,PWM |400~5000ppm | 50ppm | 23.4€ | 5V|[Library](https://pypi.org/project/mh-z19/)| [Datasheet](https://pdf1.alldatasheet.net/datasheet-pdf/view/1303687/WINSEN/MH-Z19C.html) | |
|SGP30|metal-oxide gas|I²C |400 ppm to 60000 ppm |from 1 ppm to 31 ppm| |21.47€ |3v-5v |[Library](https://pypi.org/project/sgp30/) |[Datasheet](https://cdn.shopify.com/s/files/1/0176/3274/files/Sensirion_Gas_Sensors_SGP30_Datasheet_EN-1148053.pdf?v=1603894740)| eco₂ sensor. Operating range: -40 to +85°C|
|CCS811| | | | | | | | | | |
| | | | | | | | | | | |



## Infrared camera
| Sensor        | Sensor type   | Interface  | Range     | Resolution | Price       | Library | Datasheet | Notes |
| :-----------: | :----------:  | :-------:  | :-------: | :--------: | :------:  | :--------------: | :-----------:|:-----------:|
|MLX90640|Visual IR thermometers|  I²C | | |  |[Library](https://github.com/adafruit/Adafruit_CircuitPython_MLX90640)  |[Datasheet](https://cdn.sparkfun.com/assets/7/b/f/2/d/MLX90640-Datasheet-Melexis.pdf)| | 
|OV5647 | | | |1080P |25 €| |[Datasheet](https://www.uctronics.com/download/Image_Sensor/OV5647_DS.pdf) |[Example](https://thepihut.com/products/raspberry-pi-night-vision-camera) | 
| Raspberry Pi  Module V2| NoIR Camera| | | 1080P| 29.99 € | |[Datasheet](https://www.raspberrypi.org/documentation/hardware/camera/) | | 
|AMG8833 | IR thermal camera |I²C | | |38.07 € | | [Datasheet](https://cdn-learn.adafruit.com/assets/assets/000/043/261/original/Grid-EYE_SPECIFICATIONS%28Reference%29.pdf)| | 
