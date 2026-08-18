Steps:
1. Install necessary libraries in the Arduino IDE:

    For BMP280: Adafruit BMP280 library or Adafruit Unified Sensor library.
    For OLED: Adafruit GFX and Adafruit SSD1306.

2. Wiring:

    BMP280 (I2C):
        VCC to Pico 3.3V
        GND to GND
        SCL to Pico I2C clock (e.g., GP5) 
        SDA to Pico I2C data (e.g., GP4)
    BMP280 (SPI):
        VCC to 3.3V
        GND to GND
        CS to Pico GP5
        SCK to Pico GP2
        MISO to Pico GP4
        MOSI to Pico GP3
    OLED (I2C):
        VCC to 3.3V
        GND to GND
        SCL to Pico I2C clock (same as BMP280) to SCK
        SDA to Pico I2C data (same as BMP280) to SDO
