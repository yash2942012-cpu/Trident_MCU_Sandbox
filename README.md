# Trident_MCU_Sandbox

Trident MCU Sandbox this board is a combined version of Arduino Nano, ESP32 32E, Raspberry Pi Pico micro-controllers. Also has a battery holder and a battery protection plus charging circuit. This board also features a Micro SD card slot. Also have three OLEDs 1 for each micro-controller. 

This is the OSHWLab view only link for this project

https://oshwlab.com/yash2942012/project_jpczxhkt

<img width="1703" height="923" alt="ChatGPT Image Aug 13, 2026, 08_15_56 PM" src="https://github.com/user-attachments/assets/2b05f2f2-709c-4bbd-922d-9a81f43b723f" />

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



