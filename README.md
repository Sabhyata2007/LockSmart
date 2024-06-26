# Lock System Project Using Arduino and IoT

## Overview

This project is an advanced lock system that integrates Bluetooth sensors, an Arduino microcontroller, a keypad sensor, and fingerprint authentication from smartphones for enhanced security and convenience. A mobile application, developed on the Modular platform, communicates with the Bluetooth module, providing a seamless user experience. The project leverages IoT technology to connect the physical lock system with the digital app.

## Table of Contents

- [Features](#features)
- [Hardware Requirements](#hardware-requirements)
- [Software Requirements](#software-requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Bluetooth Sensor Integration**: Enables wireless communication between the lock system and the mobile application.
- **Arduino-Based**: Provides a reliable and customizable platform for the lock system.
- **Keypad Sensor**: Allows users to enter a password manually as an alternative to Bluetooth access.
- **Fingerprint Authentication**: Uses smartphone fingerprint sensors for added security and ease of use.
- **Mobile App**: Developed on Modular to facilitate seamless communication with the Bluetooth module.
- **IoT Integration**: Connects the physical lock system with the digital app for enhanced functionality and user experience.

## Hardware Requirements

- Arduino (e.g., Arduino Uno)
- Bluetooth Module (e.g., HC-05)
- Keypad Sensor (4x4 keypad)
- Lock mechanism (e.g., servo motor)
- Breadboard and jumper wires
- Power supply

## Software Requirements

- Arduino IDE
- Modular platform for app development
- Git

## Installation

### Arduino Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/username/my-awesome-project.git
   cd my-awesome-project


2. **Upload the Code**:
  -Connect your Arduino to your computer.
  -Select the correct board and port in the Arduino IDE.
  -Upload the code to the Arduino.
  -Mobile App Setup
  - Open the Kodular Platform:
  - Export the app project files from the kodular_app directory.
  - Download app

   
3. **Configure Bluetooth Communication**:

- Ensure the app is set up to communicate with the Bluetooth module using the correct UUID and settings.

## Usage

1. **Power the System**:
  - Connect the Arduino and ensure all components are powered.
    
2. **Connect via Bluetooth**:
  - Open the mobile app and connect to the Bluetooth module.
   
3. **Enter Password**:
  - Use the keypad sensor to manually enter the password if Bluetooth is not available.
     
4.  **Control the Lock**:
  - use the mobile app to lock or unlock the system.
    
5.  **Authenticate with Fingerprint**:
  - Use the smartphone's fingerprint sensor for secure authentication

## License
  This project is licensed under the MIT License - see the LICENSE file for details.
