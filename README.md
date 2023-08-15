# ESP32-WROOM-32 with round 240x280 TFT using the SPI ST7789 interface controller

- Example project to setup the round 240x280 TFT screen connected to an ESP32-WROOM-32 using PlatformIO IDE for VSCode.
- The screen is using the SPI ST7789 interface controller, with a CS pin which is pulled down to ground.
- I'm using the bodmer/TFT_eSPI display driver library.
- The platformio.ini file has the screen size and pins set for this particular screen.
- No manual change is required inside the TFT_eSPI library user setup, to set the drivers or pin definitions.  All of the configuration is in the platformio.ini file.

1. [Pin connection diagram](docs/ESP32Wroom-ST7789.png)
2. [Test program displaying on screen](docs/ESP32WROOM32-ST7789-Test-Program.jpg)

## References
[Using the ST7789 with an ESP32](https://thesolaruniverse.wordpress.com/2021/11/05/displaying-color-pictures-on-a-240x240-tft-screen-with-st7789-controller-with-an-esp32-wroom-32/)