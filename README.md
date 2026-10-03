# Electronic Dice (Zar Electronic)

This repository contains the schematic, PCB layout, and manufacturing files for a digital electronic dice circuit. The project was designed using OrCAD Capture and Allegro PCB Editor.

## How It Works
The circuit uses an oscillator to generate rapid clock pulses when a button is pressed. These pulses are fed into a counter, and the binary output is decoded to drive a standard 7-segment display, simulating the roll of a dice.

## Core Components
Based on the schematic, the design utilizes the following main components:
* **NE555 (IC1):** Configured as an astable multivibrator to generate the clock signal.
* **74LS192 (IC2):** A synchronous up/down decade counter that processes the clock pulses.
* **74LS247 (IC3):** A BCD-to-7-segment decoder/driver.
* **LTS-542 (DS1):** A 7-segment LED display to show the final "rolled" number.
* **Pushbuttons:** Used to trigger the roll and interact with the circuit.

## Schematic Preview

<img width="1082" height="545" alt="image" src="https://github.com/user-attachments/assets/840b36e0-6002-4f8a-9cbd-3121afd2b3b4" />



## Manufacturing
All necessary Gerber and drill files for PCB fabrication have been compiled into a single archive. 
You can download the production files here: `Fisiere_fabricatie.rar`
