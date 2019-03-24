# raspberry-oled-monitor
Raspberry Tutorial
How to use OLED i2c with Raspberry Pi Display system Monitor with icons from Font Awesome

Check if the display device is connected
sudo i2cdetect -y 1
----
Clone Adafruit Python SSD1306 library
git clone https://github.com/adafruit/Adafruit_Python_SSD1306
----
Go to the cloned repository and execute
sudo python setup.py install
----

after editing of this line don't forget to reboot your RPi
----
Run the script by
python monitor.py
