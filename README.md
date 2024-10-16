# PS/2 Protocol Decoder & Loading Animation

## Introduction

This project implements an efficient method to decode basic keyboard inputs into binary numbers using an FPGA. The system interprets the PS/2 protocol, an old-fashioned protocol used to interface keyboards with various devices. The project aims to create a device and logic that allows users to input characters and receive their binary representation as output.

## Design Specifications

### Inputs:
- PS/2 Clock
- PS/2 Data
- Switch (for mode selection)
- FPGA Clock (50MHz)

### Output:
- LED Outputs (representing encoded PS/2 protocol or loading animation)

## Hardware Design

The project uses a single module called "prj" which controls all functionalities:

1. Interfaces with the PS/2 keyboard
2. Processes keyboard output
3. Displays PS/2 binary representation on FPGA LEDs
4. Implements a loading animation controlled by arrow keys

The mode of operation (decoder or loading animation) is controlled by a switch.

## Functional Simulation

The design was validated through:
- Simulating PS/2 clock and data input signals
- Verifying correct conversion to binary representation
- Testing the loading animation mode
- Simulating fast typing to ensure correct timing functions

## Design Implementation

The implementation process involved:
1. Synthesis: Converting RTL design into a netlist of logic gates and flip-flops
2. Place and Route (PAR): Assigning specific locations on the FPGA chip for both designs
3. Non-behavioral simulations: Verifying design correctness, performance, and timing

## Results and Discussion

- Successfully decoded PS/2 keyboard inputs into binary numbers on the FPGA
- Implemented a smooth transition between encryption mode and loading animation mode
- Achieved synchronization between keyboard inputs and FPGA outputs using the PS/2 clock

## Conclusion

The project successfully:
- Decoded keyboard inputs into binary numbers
- Displayed results on the FPGA
- Implemented a loading animation feature
- Demonstrated efficient communication between PS/2 keyboard and FPGA
- Achieved smooth switching between decoding and animation modes

## Team Members

- Al Muala Talal Al Maawali (ID: 135591)
- Omar Masoud AL Alawi (ID: 123901)

*Sultan Qaboos University*  
*Department of Electrical & Computer Engineering*  
*Course: ECCE5214 - Advanced Logic & Computer Interfacing*

## Additional Information

For more details on the PS/2 protocol and keycodes, refer to the PS/2 Keycode map in the project documentation.
