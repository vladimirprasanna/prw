# PRW Firmware - Addon Steering Wheel Support

### Project by Vladimir Prasanna

Welcome to the official repository for the PRW project!

## Project Description

This project introduces firmware that enables the PRW base to support additional addon steering wheels while fully maintaining **force feedback** functionality and ensuring compatibility with **PS5** and **PC** (**Xbox** hasn’t been tested yet, but it should work).

Additionally, the project includes the layout for a **PCB** based on a **Raspberry** microcontroller, allowing users to further customize the hardware and get the most out of their racing setup.

## Main Features

- **Addon steering wheel support**: The firmware allows you to connect additional steering wheels to the PRW.
- **Full force feedback**: You will not lose any force feedback functionality when using custom addon steering wheels.
- **Multi-platform compatibility**: Works seamlessly on both **PC**, **PlayStation 5** and **Xbox** (this last one yet to test).
- **PCB layout included**: The PCB layout based on the Raspberry processor is attached to the project to facilitate hardware modifications.
- **Easy installation**: The update procedure is simple and well-documented.

## Requirements

- PRW
- Raspberry Pi Pico board for implementing the PCB layout

## Firmware Installation

To upload the firmware to the add-on custom wheel, follow these steps:
1. Press the "reset" button* on the circuit board.
2. While holding down the "reset" button, connect the board to your PC/Mac via USB.
3. A file explorer window will automatically pop up, showing the contents of the board’s mass storage (or a mass storage disk on MacOs).
4. Release the "reset" button after completing the step 3.
5. Drag and drop the .uf2 file (available in the repository) into the opened window.
6. Once the transfer is complete, the firmware will be automatically uploaded!

## Contributions

Any suggestions or contributions to improve this project are welcome!
