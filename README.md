# Raspberry-Pi-Pico-Bluetooth-Test-with-MX-01P-Module
This project aims at testing the module MX-01P, which will be connected to Raspberry Pi Pico and work.


# Abstract
This project aims at testing the module MX-01P, which will be connected to Raspberry Pi Pico and work.
You can find my relative video on Bilibili, [拔剑四顾心茫然](https://www.bilibili.com/video/BV175E7zkEra).

# Introduction
- **Raspberry Pi Pico**
  There is a detailed introduction on [Pico-series Microcontrollers - Raspberry Pi Documentation](https://www.raspberrypi.com/documentation/microcontrollers/pico-series.html).
  In this project, I will use it to connect with a Made-in-China Bluetooth Module MX-01P to create a small application with it, which is to make the LED (GP25) work on different levels through PWM.

- **MX01-P**
  A Made-in-China Bluetooth Module. I bought it at an **EXTREMELY LOW** price--- 40 cents RMB.
  There are 4 pins on the board, including VCC, RX, TX, and GND.

# Detailed Description
- **Wiring Table**

  | MX-01P | Raspberry Pi Pico |
  | ------ | ----------------- |
  | VCC    | 3V3               |
  | RX     | GP0               |
  | TX     | GP1               |
  | GND    | GND                  |

- **Bluetooth Module Presetting** (OPTIONAL)
  You may do some *PREVIOUS SETTTNGS* to the MX-01P according to the user guide (I will upload it to this project later), like changing its name, setting its Baud Rate and so on.
  You should connect it to an USB-TTL Converter and use your computer to modify it. 
  In this application, I chose to rename it as MX01-P and set its Baud Rate to 115200.
  After that, you can enjoy it with your cellphone and other devices support Bluetooth.

- **Download the MicroPython Program**
  Download the **main.py** to your Raspberry Pi Pico and enjoy!

# After All
Anyway, I sincerely appreciate you all to evolve in my first repository on Github. Since it is my fist try, there must be some mistakes and issues in it. I will be very grateful if you could find them and inform me to correct them. 
