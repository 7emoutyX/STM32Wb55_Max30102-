# STM32Wb55 Max30102 OLED Heart Rate Monitor

![PCB Layout](https://github.com/7emoutyX/STM32Wb55_Max30102-/assets/110437117/1571395d-6752-47fd-9795-f8e7ba9c1c4b)

![Schematic](https://github.com/7emoutyX/STM32Wb55_Max30102-/assets/110437117/f1eb4304-4232-4c6d-b47a-ce21aca05a18)


## Overview
This project implements a heart rate monitor using the STM32Wb55 microcontroller, Max30102 sensor, and an OLED display. The system measures heart rate and oxygen levels and displays the readings on the OLED display.

## Results : 
![pcb1](https://github.com/7emoutyX/STM32Wb55_Max30102-/assets/110437117/6ca194da-a970-4d87-a31f-d1de08b8fee6)
![pcb2](https://github.com/7emoutyX/STM32Wb55_Max30102-/assets/110437117/0389af28-e620-437b-8434-b77ff27135d9)
![pcb3](https://github.com/7emoutyX/STM32Wb55_Max30102-/assets/110437117/9a810fb8-d1a1-42d6-a91e-a56b31cb0e08)
# Render has been done with Blender3D

## Table of Contents
1. [Hardware Requirements](#hardware-requirements)
2. [Software Requirements](#software-requirements)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Contributing](#contributing)
6. [License](#license)

## Hardware Requirements
To build this project, you'll need the following components:
- STM32Wb55 development board
- Max30102 sensor module
- OLED display (I2C)

## Software Requirements
To compile and run the project, you'll need the following software:
- STM32CubeIDE
- STM32Wb55 firmware libraries
- Max30102 driver library
- OLED display driver library

## Installation
1. Clone this repository to your local machine.
2. Open the project in STM32CubeIDE.
3. Configure the project settings according to your setup.
4. Install the necessary libraries for STM32Wb55, Max30102, and the OLED display.
5. Build the project and upload it to the STM32Wb55 board.

## Usage
1. Connect the Max30102 sensor and OLED display to the STM32Wb55 board.
2. Power on the board.
3. The OLED display will show real-time heart rate and oxygen level readings.
4. Use the provided buttons or interface to interact with the system as needed.

## Contributing
Contributions to this project are welcome! If you find any bugs, have suggestions for improvements, or would like to add new features, please open an issue or submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
