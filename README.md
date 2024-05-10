
# RaspberryPi-Arduino-Serial-Communication

## Overview
This repository provides a project for connecting Raspberry Pi 4 and Arduino Uno R3 via serial communication. It includes sample code for minimal serial communication between the two devices.

## Hardware Configuration
- **Microcontroller**: Arduino Uno R3
- **Single-board Computer**: Raspberry Pi 4
- **Connection Method**: Serial communication using a LAN cable

For detailed hardware setup and connection information, please refer to the article [here](https://murasan-net.com/index.php/2024/01/22/raspberry-pi-arduino-uno-uart/).

## How to Use
This repository contains two programs:

1. `arduino_to_raspberrypi_serial.ino` - A program to be run on Arduino Uno R3, which sends the message "Hello, Raspberry Pi" every two seconds.
2. `raspberrypi_serial_receiver.py` - A program to be run on Raspberry Pi 4, which receives and displays messages from Arduino.

## Setup
Before starting the project, please follow these steps to set up:

1. Use Arduino IDE to upload `arduino_to_raspberrypi_serial.ino` to Arduino Uno.
2. Python and the `pyserial` package are required on Raspberry Pi. Install them with the following commands:

```bash
sudo apt update
sudo apt install python3-pip
pip3 install pyserial
```

3. Execute `raspberrypi_serial_receiver.py` on the Raspberry Pi.

## License
This project is released under the MIT License. For details, see the LICENSE file.

## Author
Murasan201  
[https://murasan-net.com/](https://murasan-net.com/)

## Acknowledgements
Thanks to everyone who contributed to this project.
