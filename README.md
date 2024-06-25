# CANShield

STM32 Nucleo-64 Development Shield to connect NXP TJA1443 CANbus chip with some memory and GPS probe interface.

## Table of Contents
- [About](#about)
- [Features](#features)
- [Circuit Description](#circuit-description)
- [Hardware Requirements](#hardware-requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## About
CANShield is a development shield designed for the STM32 Nucleo-64 board. It integrates an NXP TJA1443 CANbus transceiver, additional memory, and a GPS probe interface to facilitate the development and testing of CANbus applications. This shield provides a versatile and powerful platform for engineers and developers working on CANbus networks and applications, offering the tools needed to prototype and experiment with CAN-FD protocols.

## Features
- **Compatibility**: Fully compatible with STM32 Nucleo-64 boards, providing a seamless integration experience.
- **NXP TJA1443 CANbus Transceiver**: High-speed CAN-FD transceiver for robust and reliable CANbus communication.
- **Integrated Memory**: Additional memory for data storage, enabling complex applications and logging capabilities.
- **GPS Probe Interface**: Easy integration with GPS modules for applications requiring location data.
- **KiCad Design Files**: Open-source design files available, allowing for easy modifications and customizations.

## Circuit Description
This project includes the development and implementation of a custom development board with the NXP TJA1443 CAN-FD chip. The board connects to an Nucleo-64 development board, specifically the Nucleo-32G0B1, to fully exploit the capabilities of the CAN-FD interface.

The main purpose of this project is to utilize the full potential of the NXP TJA1443 chip in a CAN-FD network. By integrating this chip with the Nucleo-32G0B1, we aim to develop and test various protocols within the CAN network, providing a robust platform for CAN-FD communication.

Key Features:
- **NXP TJA1443 CAN-FD Chip**: High-speed CAN transceiver with advanced features for CAN-FD networks.
- **Nucleo-32G0B1 Compatibility**: Utilizes the STM32G0 microcontroller with integrated CAN-FD support.
- **Custom Development Board**: Tailored design for easy integration and testing of CAN-FD protocols.
- **Protocol Development and Testing**: Focus on creating and evaluating various protocols within the CAN network.

This project provides a comprehensive platform for developing and testing CAN-FD protocols, leveraging the capabilities of the NXP TJA1443 chip and the Nucleo-32G0B1 development board.

## Hardware Requirements
To get started with CANShield, you will need the following hardware components:
- **STM32 Nucleo-64 Board**: The main development board that hosts the STM32 microcontroller.
- **CANShield Board**: The custom shield that integrates the NXP TJA1443 CAN-FD transceiver, memory, and GPS interface.
- **GPS Probe (Optional)**: A GPS module for applications requiring geographic data.
- **Power Supply**: Appropriate power supply to power the Nucleo-64 and CANShield boards.

## Installation
1. **Clone the Repository**: Start by cloning the CANShield repository to your local machine.
    ```sh
    git clone https://github.com/MootSeeker/CANShield.git
    ```
2. **Open KiCad Project**: Open the KiCad project files located in the `CANShield` directory to review the schematics and PCB layout.
3. **Assemble the Shield**: Assemble the CANShield board according to the provided schematics and Bill of Materials (BOM). Ensure all components are correctly soldered and connected.
4. **Attach to Nucleo-64**: Connect the assembled CANShield board to the STM32 Nucleo-64 board.

## Usage
1. **Setup Hardware**: Attach the CANShield to the STM32 Nucleo-64 board. Connect the GPS probe to the shield if needed.
2. **Power Up**: Supply power to the setup using an appropriate power source.
3. **Program the STM32**: Upload your CANbus application code to the STM32 microcontroller using your preferred development environment (e.g., STM32CubeIDE).
4. **Monitor Communication**: Use CANbus monitoring tools to observe and debug the communication on the CANbus network. This can be done using software tools or hardware analyzers.

## Contributing
Contributions are welcome! Whether you have suggestions for improvements, bug fixes, or new features, please feel free to contribute. Here’s how you can get involved:
- **Open an Issue**: Report bugs or suggest features by opening an issue on the GitHub repository.
- **Submit a Pull Request**: Fork the repository, make your changes, and submit a pull request for review.
- **Documentation**: Help improve the project documentation by adding examples, tutorials, or clarifications.

## License
This project is licensed under the MIT License. You are free to use, modify, and distribute this project as per the terms of the license. See the [LICENSE](LICENSE) file for more details.

## Contact
For questions, feedback, or more information, please contact [MootSeeker](https://github.com/MootSeeker). We look forward to hearing from you and seeing how you use CANShield in your projects!
