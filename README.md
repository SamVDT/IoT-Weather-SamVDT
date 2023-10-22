# Internet of Things (IoT) Weather Station

The Internet of Things (IoT) is a term used to describe devices that use sensors, can process data, exchange information with other devices, and much more. This project is designed to explore the basics of IoT and how it can be used in innovative and interesting ways. The project is centered around a weather station that collects environmental measurements using a DHT11 humidity sensor and displays the data on a server. This project is a great introduction to the core principles of IoT.

## Parts

### Breadboard
The breadboard is an essential component that allows you to create temporary circuits for various projects. It is crucial for setting up IoT projects, such as this weather station.

### ESP32 Dev Module
The ESP32 Dev Module is the microcontroller board used for this project. It is a versatile and powerful board with built-in support for the Arduino IDE, a generous number of programmable GPIO pins, and integrated flash and RAM for storing code and data.

### DHT11 Humidity Sensor
The DHT11 Humidity Sensor is a cost-effective module used with the ESP32. It provides accurate humidity and temperature measurements, making it suitable for IoT weather-related projects.

- Pin 1: VCC
- Pin 2: DATA
- Pin 3: NC (No Connection)
- Pin 4: GND

### Breadboard Jumper Wires
Breadboard jumper wires are used to create connections between components on the breadboard. They simplify the circuit assembly process.

## Setup of VS Code and Arduino (For Macbook Pro)

To get started with this project, follow these steps:

1. Download [Visual Studio Code](https://code.visualstudio.com/download) and open it.
2. Download [Arduino IDE](https://www.arduino.cc/en/software) and open it.
3. In Visual Studio Code, press `Cmd + ,` to open the settings.
4. Insert the following URL into the "Additional Board Manager URLs": https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
5. 5. Go to "Tools" > "Board" > "Boards Manager," search for "ESP32," and install it.
6. Select your ESP32 module, connect it to your computer, and choose the appropriate port.

## Usage

IoT, like this weather station, offers numerous practical applications. You can use it to:

- Monitor weather conditions in specific locations, such as a child's room or your home.
- Integrate it into smart homes to control heating and cooling systems.
- Gather data for gardening, energy efficiency, and more.
- Receive alerts for weather-related events, making it easier to plan activities.

IoT has endless possibilities, and this project is just the beginning of what you can achieve.

## Problems Faced

During the course of this project, I encountered several challenges, including hardware failures and setbacks. The flame sensor, which was initially intended for the project, melted and broke, requiring a complete restart. Additionally, the Dev Module experienced an irreparable breakdown, leading to errors toward the end of the project's timeline. Despite these challenges, I adapted and decided to create a weather station.

## Errors

One of the errors I faced during this project was the "An error occurred while fetching data." To resolve this, I had to reset my number in Visual Studio Code and align it with the IP address.

Another error, the 'UND_ERR_CONNECT_TIMEOUT,' proved difficult to fix and sometimes rendered my code unrunnable.

## Project Overview

This project provided valuable insights into IoT and its real-world applications. I learned to set up servers and run unique projects while gaining a deeper understanding of IoT. Despite facing challenges and setbacks, this project taught me resilience in the face of failure. I look forward to future opportunities and successes in the world of IoT.

## Bibliography

- [Espressif ESP32 Dev Module](https://docs.platformio.org/en/latest/boards/espressif32/esp32dev.html)
- [Getting Started with the ESP32 Development Board](https://randomnerdtutorials.com/getting-started-with-esp32/)
- [How to Get Started Coding for Arduino on MacOS Ventura](https://appleinsider.com/inside/macos-ventura/tips/how-to-get-started-coding-for-arduino-on-macos-ventura)
- [Installing ESP32 in Arduino IDE Mac OS X and Linux](https://randomnerdtutorials.com/installing-the-esp32-board-in-arduino-ide-mac-and-linux-instructions/)
- [What Is IoT? - Internet of Things Beginner’s Guide - AWS](https://aws.amazon.com/what-is/iot/)

