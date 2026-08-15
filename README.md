# Trident_MCU_Sandbox

Trident MCU Sandbox this board is a combined version of Arduino Nano, ESP32 32E, Raspberry Pi Pico micro-controllers. Also has a battery holder and a battery protection plus charging circuit. This board also features a Micro SD card slot. Also have three OLEDs 1 for each micro-controller. 

This is the OSHWLab view only link for this project

https://oshwlab.com/yash2942012/project_jpczxhkt

## Technical Specs

 Power Supply
 - Charging Module - TP4056_C382139
 - Boost Converter - MT3608 ( for 5V )
 - Protection ICs - DW01A_C841289 and FS8205A
 - Battery Holder - BH-18650-B1BA007 COPY
 - USB - TYPE-C-31-M-12
 - LDO - AMS1117-3.3V ( for 3V3 )

 Arduino
 - Main Module - ATmega328P-AU
 - USB to UART chip - CH340G
 - USB - TYPE-C-31-M-12
 - 16MHz SMD Crystal Oscillator
 - AMS1117-3.3V LDO for OLED

ESP32
- Main Module - ESP32-WROOM-32E (8MB)
- USB to UART chip - CP2102N-A02-GQFN24R
- USB - TYPE-C-31-M-12
- LESD5D5.0CT1G_C5246195 TVS diodes
- NPN BJT - SS8050-G

Raspberry Pi Pico
- Main Module - RP2040
- USB - TYPE-C-31-M-12
- 12MHz SMD Crystal Oscillator
- SPI Flash Memory chip - W25Q128JVSIQ_C2613931

Addons
- OLED - HS96L03W2C03
- Micro SD Card Slot - 1040310811
- Neo Pixel LED - WS2812B-B

<img width="1703" height="923" alt="ChatGPT Image Aug 13, 2026, 08_15_56 PM" src="https://github.com/user-attachments/assets/2b05f2f2-709c-4bbd-922d-9a81f43b723f" />

YOU CAN ALSO DOWNLOAD THE GERBER, CPL AND BOM FILE FOR DIRECT PCB MANUFACTURING! 

## HOW TO USE
- Put the Batteries in ensure they have an unprotected cap
- Short the Male Header Pins Labeled 'Board' to power ON the Board
- Short the Male Header Pins Labeled 'ATmega328P-AU' to power ON the Arduino Nano only part
- Short the Male Header Pins Labeled 'ESP32-WROOM-32E (8MB)' to power ON the ESP32 only part
- Short the Male Header Pins Labeled 'RP2040' to power ON the Raspberry Pi Pico only part
- Short the Male Header Pins Labeled 'AT_OLED' to power ON the OLED connected to Arduino Nano
- Short the Male Header Pins Labeled 'ESP_OLED' to power ON the OLED connected to ESP32
- Short the Male Header Pins Labeled 'RP_OLED' to power ON the OLED connected to Raspberry Pi Pico
- Short the Male Header Pins Labeled 'Micro SD' to power ON the Micro SD Card Slot
- Use the PC4 as SDA and PC5 as SCL to control the AT_OLED
- Use the  as SDA and PC5 as SCL to control the AT_OLED
- Use the PC4 as SDA and PC5 as SCL to control the AT_OLED



