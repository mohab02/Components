# Components
## Temperature sensors:
### Types of temperature sensors:
* Thermocouples
* Resistance temperature detectors (RTD)
* Thermistors
* Semiconductors based integrated circuits

| Sensor        | Sensor type   | Interface  | Range     | Resolution | Price    | Supply Voltage Range   | Library | Datasheet | Feature |
| :-----------: | :----------:  | :-------:  | :-------: | :--------: | :------: | :-------------------:  | :--------------: | :-----------:|:-----------:|
| MAX31855      | Thermocouple  |    SPI     | Depends on the type | 14-Bit;0.25°C |12.60 €|3.0V< VCC< 3.6V |[Library](https://github.com/Tuckie/max31855) | [Datasheet](https://bit.ly/366CidX)  | |
| MCC134        | Thermocouple  | general purpose I/O (GPIO) | Depends on the type | ADC resolution: 24 bits |137,00 € | 3.3 V | [Library](https://github.com/mccdaq/daqhats) |[Datasheet](https://www.mccdaq.com/PDFs/specs/DS-MCC-134.pdf)  | up to 4 thermo couples|
|DFR0558  | Thermocouple K Type |  I²C |   -270°C~1372°C   | 14 bit  |  €20,93  | 3.3V and 5V |[Library](https://github.com/DFRobot/DFRobot_MAX31855)|[Datasheet](https://media.digikey.com/pdf/Data%20Sheets/DFRobot%20PDFs/DFR0558_Web.pdf)| Probe can be attached |
| ADS1118 |Thermocouple K-Type|SPI|  –200°C to +1250°C  |16bit; 0.03125°C|111,52 €| 2v~7v |[Library](https://github.com/jonathanimb/ADS1118)|[Datasheet](https://www.ti.com/lit/ds/symlink/ads1118.pdf)| Ultrasmall, low power consumption |
|MCP9600|Thermocouple|I²C|Depends on the type|0.0625°C|5,97€|2.7v~5.5v|[Library](https://github.com/pimoroni/mcp9600-python)|[Datasheet](https://ww1.microchip.com/downloads/en/DeviceDoc/MCP960X-Data-Sheet-20005426.pdf)|  |
|MAX31850K| Thermocouple | 1-Wire|Depends on the type |14bit;0.25°C|21,79€ |3.3V |[Library](https://github.com/Seeed-Studio/Seeed_MAX31850K)|[Datasheet](https://cdn-shop.adafruit.com/datasheets/MAX31850-MAX31851.pdf)|  |
|  |  |   |    |  |    |  |  |    |  |
|  |  |   |    |  |    |  |  |    |  |

