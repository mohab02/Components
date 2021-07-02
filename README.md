# Components
## Temperature sensors:
### Types of temperature sensors:
* Thermocouples
* Resistance temperature detectors (RTD)
* Thermistors
* Semiconductors based integrated circuits

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

## Infrared camera
| Sensor        | Sensor type   | Interface  | Range     | Resolution | Price       | Library | Datasheet | Notes |
| :-----------: | :----------:  | :-------:  | :-------: | :--------: | :------:  | :--------------: | :-----------:|:-----------:|
|MLX90640|Visual IR thermometers|  I²C | | |  |[Library](https://github.com/adafruit/Adafruit_CircuitPython_MLX90640)  |[Datasheet](https://cdn.sparkfun.com/assets/7/b/f/2/d/MLX90640-Datasheet-Melexis.pdf)| | 
|OV5647 | | | |1080P |25 €| |[Datasheet](https://www.uctronics.com/download/Image_Sensor/OV5647_DS.pdf) |[Example](https://thepihut.com/products/raspberry-pi-night-vision-camera) | 
| Raspberry Pi  Module V2| NoIR Camera| | | 1080P| 29.99 € | |[Datasheet](https://www.raspberrypi.org/documentation/hardware/camera/) | | 
|AMG8833 | IR thermal camera |I²C | | |38.07 € | | [Datasheet](https://cdn-learn.adafruit.com/assets/assets/000/043/261/original/Grid-EYE_SPECIFICATIONS%28Reference%29.pdf)| | 
