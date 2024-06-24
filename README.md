# CANShield

STM32 Nucleo-64 Development Shield to connect NXP TJA1443 CANbus chip with some memory and GPS probe interface.

## Table of Contents
- [About](#about)
- [Features](#features)
- [Hardware Requirements](#hardware-requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## About
CANShield is a development shield designed for the STM32 Nucleo-64 board. It integrates an NXP TJA1443 CANbus transceiver, additional memory, and a GPS probe interface to facilitate the development and testing of CANbus applications.

## Features
- Compatible with STM32 Nucleo-64 boards
- NXP TJA1443 CANbus transceiver
- Integrated memory for data storage
- GPS probe interface
- KiCad design files for easy modifications

## Hardware Requirements
- STM32 Nucleo-64 board
- CANShield board
- GPS probe (optional)
- Power supply

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/MootSeeker/CANShield.git
    ```
2. Open the KiCad project files in the `CANShield` directory.
3. Assemble the shield according to the provided schematics and bill of materials (BOM).

## Usage
1. Attach the CANShield to the STM32 Nucleo-64 board.
2. Connect the GPS probe to the shield (if needed).
3. Power up the setup and program the STM32 with your CANbus application code.
4. Monitor CANbus communication using your preferred tools.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For questions or feedback, please contact [MootSeeker](https://github.com/MootSeeker).

