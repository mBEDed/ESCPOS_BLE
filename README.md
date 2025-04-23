# ESC/POS Printer Library

A Library to control an ESC printer by an ESP32 via Bluetooth BLE.

## Requirements

An ESP32 board with Bluetooth BLE and an ESC Bluetooth BLE thermal printer, knowing the UUID of the service and the characteristic.

## Tested

- Pretty sure it's Chinese (But they say it's **MADE IN INDIA**) ESC/POS printer called "B-41" & ESP32-C3, ESP-WROOM-32

[![IMAGE ALT TEXT HERE](https://a.media-amazon.com/images/I/41mCgtYHRnL._SX300_SY300_QL70_FMwebp_.jpg)]( )

- You can get it from the links below **(NON-AFFILIATED)**
    - https://www.seznik.in/products/seznik-bluetooth-receipt-printer-58-mm-rechargeble-inkless-thermal-receipt-printer-mobile-desktop-compatible-receipt-printer-1
    - https://amzn.in/d/fw2ATRD

## How convert image

Using the image2cpp project to generate the byte array

https://javl.github.io/image2cpp/

## How to use the library

It is available in the Arduino library manager or you can download the zip to the local /Arduino/libraries path of your IDE, once installed you can see the example in the menu or open it from the examples folder.


## If the library was useful to you
[![](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86)](https://github.com/sponsors/userHarpreet)


## Based on
https://github.com/cranties/escposprinter and https://github.com/rnrobles/esc-thermal-printer-ble.git

