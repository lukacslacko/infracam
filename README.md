# infracam

1. Enable I2C with `sudo raspi-config`
2. Add libraries:
  a. `sudo apt install python3-smbus`
  b. `sudo apt install i2c-tools`
3. Connect SDA - GPIO2, pin3; SCL - GPIO3, pin5; 3v3 - pin 1 or 17; GND
3. Check presence of oled: `sudo i2cdetect -y 1`
4. Install the Adafruit library:
  a. `git clone https://github.com/adafruit/Adafruit_Python_SSD1306`
  b. `cd Adafruit_Python_SSD1306`
  c. `sudo python3 setup.py install`
5. Look at the examples there.
6. `sudo apt install python3-picamzero`
