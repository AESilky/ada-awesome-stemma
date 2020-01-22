<h1 align="center">
  <img width="853" src="https://github.com/adafruit/awesome-stemma/blob/master/awesome-stemma.jpg" alt="Awesome Stemma"><br>Awesome Stemma
</h1>

> A curated list of awesome Stemma connector resources including Stemma-equipped microcontrollers and breakout boards.

Adafruit Stemma is a collection of solderless digital/analog/power/I2C connection standards based on JST PH 3 and 4 pin connectors. For smaller footprint breakout boards, the JST SH 4 pin connector may be used for I2C connections.

Stemma equipped boards may be compatible with Seed Studio Grove connectors, SparkFun Qwiic connectors or DFRobot Gravity connectors. Cross-compatibility should be checked before interconnecting Stemma/Stemma QT boards with other manufacturer boards, as there could be connector incompatibilities or voltage issues (with Qwiic boards).

## Contents

- [Guides](#guides)
- [Compatibility](#compatability)
- [Stemma Hardware](#stemma-hardware)
- [Accessories](#accessories)
- [In the news](#news)
- [Art, logos, graphics](#art)
- [Social media](#social)
- [Contributing](#contributing)

## Guides

- [Adafruit STEMMA and STEMMA QT](https://learn.adafruit.com/introducing-adafruit-stemma-qt) - Adafruit Learning System primary guide on all things Stemma
- [Qwiic Tutorials](https://learn.sparkfun.com/tutorials/tags/qwiic) from SparkFun

## Compatibility


## Stemma Hardware

### Adafruit Microcontroller Boards with Stemma

| Microcontroller Board | Stemma Connectors | Features |
|---|---|---|
| [Feather STM32F405 Express](https://www.adafruit.com/product/4382) | 1 Stemma QT | STM32F405 Cortex M4, 168MHz, 192KB RAM, 1MB Flash |
| [PyBadge](https://www.adafruit.com/product/4200) | 1x 4 pin Stemma, 2x 3 pin Stemma | ATSAMD51J19, 120MHz, 512KB of FLASH, 192KB RAM, 2MB Flash |
| [Edge Badge](https://www.adafruit.com/product/4400) | 1x 4 pin Stemma, 2x 3 pin Stemma | ATSAMD51J19, 120MHz, 512KB of FLASH, 192KB RAM, 2MB Flash |
| [PyGamer](https://www.adafruit.com/product/4242) | 1x 4 pin Stemma, 2x 3 pin Stemma | ATSAMD51J19, 120MHz, 512KB of FLASH, 192KB RAM, 8MB Flash |
| [MONSTER M4SK](https://www.adafruit.com/product/4343) | 1x 4 pin Stemma, 2x 3 pin Stemma | ATSAMD51G19, 120MHz, 512KB of FLASH, 192KB RAM, 8MB Flash |
| [HalloWing M4](https://www.adafruit.com/product/4300) | 1x 4 pin Stemma, 2x 3 pin Stemma | ATSAMD51J19, 120MHz, 512KB of FLASH, 192KB RAM, 8MB Flash |
| [Trellis M4](https://www.adafruit.com/product/3938) | 1 4 pin Stemma | ATSAMD51G19, 120MHz, 512KB of FLASH, 192KB RAM, 8MB Flash |

### Adafruit Sensors and Peripherals with Stemma

| Board | Stemma Connectors | Features |
|---|---|---|
| [Soil Sensor](https://www.adafruit.com/product/4026) | 1 Stemma | I2C capacitive moisture sensor |
| [NeoTrellis RGB Driver](https://www.adafruit.com/product/3954) | 1 Stemma | Provides a 4x4 matrix of RGB NeoPixel lit elastomer keys |
| [Stemma Speaker](https://www.adafruit.com/product/3885) | 1 Stemma | A class D audio amplifier and an oval speaker |
| [Mini Relay, Nonlatching](https://www.adafruit.com/product/4409) | 1 Stemma | A single pole/double throw relay up to 250V AC or DC |
| [NeoPixel Strip](https://www.adafruit.com/product/3919) | 1 Stemma | 60 pixels per meter density, 30 pixels 0.5 meter |
| [Tactile Push Buttons](https://www.adafruit.com/product/4431) | 1 Stemma each | Pack of 5 breakaway tactile buttons |
| [Micro Servo](https://www.adafruit.com/product/4326) | 1 Stemma | STandard micro servo with Stemma connector |
| [TSL2561](https://www.adafruit.com/product/3611) | 1 Stemma  | Digital lux / light sensor |
| [MCP4728 Quad DAC](https://www.adafruit.com/product/4470) | 2 Stemma QT | Four 12-bit DACs with integrated EEPROM for settings |
| [LSM6DS33](https://www.adafruit.com/product/4480) | 2 Stemma QT | 6 DoF IMU accelerometer + gyroscope |
| [LIS3MDL](https://www.adafruit.com/product/4479) | 2 Stemma QT | Triple-axis magnetometer compass module |
| [LSM6DS33 + LIS3MDL](https://www.adafruit.com/product/4485) | 2 Stemma QT | 9 DoF IMU with accelerometer, gyroscope, magnetometer |
| [LSM303AGR](https://www.adafruit.com/product/4413) | 2 Stemma QT | Triple-axis accelerometer/magnetometer compass module |
| [LSM6DSOX](https://www.adafruit.com/product/4438) | 2 Stemma QT | An I2C/SPI 6 DoF accelerometer and gyroscope |
| [MPU-6050](https://www.adafruit.com/product/3886) | 1 Stemma QT | An I2C 6 DoF accelerometer and gyroscope |
| [TLV493D](https://www.adafruit.com/product/4366) | 2 Stemma QT | Triple-Axis magnetometer |
| [MLX90640 IR Thermal Camera](https://www.adafruit.com/product/4469) | 2 Stemma QT | A 24x32 array of IR thermal sensors, 110°x70° field of view |
| [PA1010D Mini GPS](https://www.adafruit.com/product/4415) | 2 Stemma QT | GPS, GLONASS, GALILEO, QZSS receiver, 1"x1" |
| [PCT2075](https://www.adafruit.com/product/4369) | 2 Stemma QT | Temperature Sensor, LM75 upgrade |
| [VCNL4040](https://www.adafruit.com/product/4161) | 2 Stemma QT | Proximity and Lux sensor |
| [DS3502](https://www.adafruit.com/product/4286) | 2 Stemma QT | I2C Digital Potentiometer |
| [LPS33HW](https://www.adafruit.com/product/4414) | 2 Stemma QT | Water resistant pressure sensor |
| [TRUST M SLS 32AIA](https://www.adafruit.com/product/4351) | 2 Stemma QT | OPTIGA Trust M RSA 1K/2K + ECC256/384 Crypto |
| [ATECC608](https://www.adafruit.com/product/4314) | 2 Stemma QT | Crypto ECDH and AES-128, SHA-256/HMAC hash |

### Qwiic Boards from SparkFun

- [Qwiic Main Page](https://www.sparkfun.com/qwiic) on Sparkfun.com
- [One page list of Qwiic products from SparkFun](https://cdn.sparkfun.com/assets/home_page_posts/3/1/7/7/SparkFun_s_Qwiic_Ecosystem.pdf)

## Accessories


## News


## Art

- [Qwiic Logos](https://cdn.sparkfun.com/assets/custom_pages/3/3/4/Qwiic-Registered-Logo.zip) from Sparkfun


## Social Media


## Contributing

Contributions and suggestions are always welcome! Please make pull requests to modify Awesome Stemma.

## License & Trademarks

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the authors have waived all copyright and related or neighbouring rights to this work.
