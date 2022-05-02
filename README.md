# Wireless USB 
Using the esp32 and FTP support, a standard micro SD to SD adapter is transformed into a wireless Card reader for use with smartphones and tablets.
Files may be transferred to SD cards, and files can also be copied from SD cards to any device that is capable of running an FTP client program.


### How to Get Started

When you open **Wireless SD.ino** in the Arduino IDE [Tested on Arudino IDE 1.8.12 and above], all of the other files will open with it as well.

### Prerequisites are required.

* [ESP-Core](https://github.com/esp8266/Arduino) - created by Ivan Grokhotkov and available on GitHub.

### Contextual relevance

Once the device has been powered on, follow the procedures outlined below to transfer data from the SD card:
```\s-> Connect to the access point "SD Reader" using the password "ASDF@123" to gain access to the system.

-> Download any FTP client application from the internet (Android - AndFTP, Windows - WinScp).

-> The host name is "192.168.12.7" and the port number is "21."

-> Enter "esp8266" as both the user name and the password.

-> Establish a connection with the server "'

## Acknowledgements and References

* [David Paiva](https://github.com/nailbuster) is a software developer. Arduino FTP server has been ported to the esp8266/esp32.

Rama Chetan Atmudi
Adithya B
Hari Kiran V