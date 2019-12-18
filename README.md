# TFTP-Arduino
TFTP Server for Arduino
Using a SPI devices to communicate with Ethernet and SPI.

Arduino IDE Version **[1.8.11](https://www.arduino.cc/en/Main/Software)**

## Tested on:
**Boards:**
Arduino Uno
Arduino Mega (2560)
Arduino M0 (SAMD21)

**Ethernet**:
Wiz5100 shield with micro-SD card

## What works
1. Send and recieve packets in netascii mode

## Current issues
1. Files more than 128kb stucks when client send file because current count block system not work well

## To Do
1. Send and recieve files more than 128kb (512b 256 packets)
2. Recieve files without timeout from client
3. Implement octet mode
4. Implement mail mode

