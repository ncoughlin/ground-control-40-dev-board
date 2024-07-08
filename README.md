# Ground Control 40 Dev Board

The Ground Control 40 Dev Board is an **open source** 40% ortho-linear keyboard shell with exposed pin header, designed for rapid prototyping with any micro-controller of your choice.

![ground control 40 dev > overhead](./images/ground_control_40_dev_1_1000px.jpg)

![ground control 40 dev > overhead annotated](./images/ground_control_40_dev_1_1000px_annotated.jpg)

![ground control 40 dev > side angle right](./images/ground_control_40_dev_2_1000px.jpg)

![ground control 40 dev > side angle left](./images/ground_control_40_dev_3_1000px.jpg)

![ground control 40 dev > size comparison](./images/ground_control_40_dev_4_1000px.jpg)

## Features

- Combined Rotary Encoder + 5-direction multi-switch in one (Alps RKJXT1F42001 switch)
- Split spacebar ortholinear 40% layout
- Low-profile (Choc v1 Switches)
- Folded switch Matrix to minimize required I/O pins
- HotSwap sockets

## Required Parts

⚠ Warning: Do not attempt to use any keycap profile other than CFX. It will not work. The spacing is designed specifically for this profile (which is perfectly square, not rectangular).

- 45 x Choc v1 switches
- 45 x Choc v1 hotswap sockets
- 43 x CFX 1u Keycaps
- 2 x CFX 2u Keycaps
- 2 x Choc v1 2u stabilizers
- 1 x Alps RKJXT1F42001
- 45 x Onsemi 1N4148WS diodes
- 14 x Mill-Max 1440-4-00-15-00-00-03-0 nail head pins
- 14 x Harwin H3185-05 Pin Socket
- 2 x Samtec SQT-110-01-FM-S-RA 1x10 horizontal pin socket

## Ordering

PCB's can be ordered through JLCPCB. The minimum order volume is 5 pieces per board, and there are three boards. The cost is actually quite reasonable.

Electronics components can all be found on Mouser.

Choc v1 switches available through various vendors depending on your preferred flavor.

CFX keycaps available from Chosfox and various other vendors.

## Assembly

### Required Tools

- Soldering Iron
- Hot Air Gun (for diodes)

### Order of Operations

The design consists of three PCB's.

Mounting Plate: Has no parts to assemble
Switch Plate: Holds the hotswap sockets, stabilizers, diodes and nail-head pins
Main Plate: Hold the Alps multi-switch, horizontal pin socket and board to board pin sockets

1. Install the parts that belong to each plate onto them before you attempt to combine the plates or install Choc switches.

2. After each plate is prepared, assemble the plates together. ⚠ Ensure that the stabilizers etc are all installed or else you will have to disassemble again to install them.

3. Using a piece of 150 grit sandpaper, sand the left and right sides of each switch hole on the mounting plate. This will ensure that the Choc v1 switches can snap into place without damaging them (their little clips are more fragile than a standard switch)

4. Install the switches one at a time. Start in the corners and then middle. Use an alternating pattern to give equal pressure.

## Recommended KeyMap