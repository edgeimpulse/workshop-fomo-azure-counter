# Screw/Washer Azure IoT Demo

Count number of screws and washers seen via the OpenMV camera. Send those numbers periodically to an ESP32 (via UART) that is connected to the Azure IoT Central hub. These numbers can be displayed and viewed on the dashboard.

## Hardware Connections

| Adafruit HUZZAH32 | OpenMV H7 Cam |
|:-----------------:|:-------------:|
| RX (GPIO 16/U2RXD) | P1 (UART TX) |
| GND | GND |

## Software

Install the *Azure SDK for C* Arduino library. Change the connection settings in *esp32_azure_iot_central_counter/iot_configs.h*. Upload *esp32_azure_iot_central_counter.ino* to the ESP32 board.

Copy the files in *ei-fomo-washers-and-screws-96x96-openmv-v22/* to the OpenMV camera. Feel free to run main.py from the OpenMV IDE if you wish to see the visual output.

## License

See the individual software components for their respective licenses.