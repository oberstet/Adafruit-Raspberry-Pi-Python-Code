# Adafruit's Legacy Raspberry Pi Python Code Library

## What happened to all the Raspberry Pi Python code!?

In the past this repository held all of the Raspberry Pi related Python code
that Adafruit published.  For example code to talk to sensors like the BMP085,
TCS34725, and other hardware like character LCD plates.  Over time we found it
difficult to manage so much code in a single repository, and couldn't easily put
the code on Python's package index for simple installation.  Now we've broken out
all of the previous Python code into individual GitHub repositories, and we've
loaded all of these repositories on the [Python package index](https://pypi.python.org/pypi)
so they can be installed with `pip`.

## Where do I find the new Raspberry Pi Python code?

Here is a table with each of the old libraries and a link to their new unique
GitHub repositories and easy pip install names:

| Old Library Name | New Library Location | New `pip install` Package Name | Notes |
|------------------|----------------------|------------------------|
| Adafruit_ADS1x15 | https://github.com/adafruit/Adafruit_ADS1X15 | adafruit-ads1x15 | [See guide](https://learn.adafruit.com/raspberry-pi-analog-to-digital-converters). |
| Adafruit_ADXL345 | TBD | TBD | - |
| Adafruit_BMP085 | https://github.com/adafruit/Adafruit_Python_BMP | TBD | [See guide](https://learn.adafruit.com/using-the-bmp085-with-raspberry-pi/using-the-adafruit-bmp085-python-library). |
| Adafruit_CharLCD | https://github.com/adafruit/Adafruit_Python_CharLCD | TBD | [See new character LCD guide](https://learn.adafruit.com/character-lcd-with-raspberry-pi-or-beaglebone-black/overview). |
| Adafruit_CharLCDPlate | https://github.com/adafruit/Adafruit_Python_CharLCD | TBD | [See new character LCD guide](https://learn.adafruit.com/character-lcd-with-raspberry-pi-or-beaglebone-black/overview). |
| Adafruit_DHT_Driver | https://github.com/adafruit/Adafruit_Python_DHT | - | See the [C code for reading the DHT sensor](https://github.com/adafruit/Adafruit_Python_DHT/tree/master/source/Raspberry_Pi_2) in the updated Python driver. |
| Adafruit_DHT_Driver_Python | https://github.com/adafruit/Adafruit_Python_DHT | TBD | [See updated DHT sensor guide](https://learn.adafruit.com/dht-humidity-sensing-on-raspberry-pi-with-gdocs-logging/overview) |
| Adafruit_I2C | https://github.com/adafruit/Adafruit_Python_GPIO | TBD | See [updated I2C code](https://github.com/adafruit/Adafruit_Python_GPIO/blob/master/Adafruit_GPIO/I2C.py) in the Python GPIO library.  Import with `import Adafruit_GPIO.I2C as I2C` and create an instance of `I2C.Device` instead of the old `Adafruit_I2C` class. |
| Adafruit_LEDBackpack | https://github.com/adafruit/Adafruit_Python_LED_Backpack | TBD | [See new LED backpacks guide.](https://learn.adafruit.com/led-backpack-displays-on-raspberry-pi-and-beaglebone-black/overview) |
| Adafruit_LEDpixels | TBD | TBD | - |
| Adafruit_LSM303 | TBD | TBD | - |
| Adafruit_MCP230xx | https://github.com/adafruit/Adafruit_Python_GPIO | TBD | See [updated MCP230xx code](https://github.com/adafruit/Adafruit_Python_GPIO/blob/master/Adafruit_GPIO/MCP230xx.py). |
| Adafruit_MCP3002 | TBD | TBD | - |
| Adafruit_MCP3008 | https://github.com/adafruit/Adafruit_Python_MCP3008 | adafruit-mcp3008 | [See guide](https://learn.adafruit.com/raspberry-pi-analog-to-digital-converters). |
| Adafruit_MCP4725 | TBD | TBD | - |
| Adafruit_PWM_Servo_Driver | TBD | TBD | - |
| Adafruit_TCS34725 | TBD | TBD | - |
| Adafruit_VCNL4000 | TBD | TBD | - |

## But I **need** the old code!  What can I do?

Don't worry the old Adafruit Raspberry-Pi Python code can be found in the
legacy branch of this repository.  This is a snapshot of the old code before it
was refactored into individual libraries. **Note this legacy code will not be
maintained!**
