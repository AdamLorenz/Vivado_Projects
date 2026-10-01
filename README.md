# Vivado Projects

This repo contains my personal Vivado project folders and local IP block repo:

## Loopback Project
Configure a loopback adder into the FPGA fabric of a PYNQ-Z2, connect it via AXI interface to the onboard processing system (PS), and implement it on the development board with an exported .xsa file including the bitstream.

Additionally, utilize Petalinux to build a custom embedded Linux operating system to include the adder hardware and a baked-in C program to interact with the memory-mapped hardware to test its functionality.

Credit to [kbralten](https://github.com/kbralten) and his repo [pynq_to_zynq](https://github.com/kbralten/pynq_to_zynq), which helped guide me through the learning process of using Vivado for the first time.
