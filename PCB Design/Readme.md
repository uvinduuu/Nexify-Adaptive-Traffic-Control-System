# Solar Power Supply Circuit

This repository contains the design and implementation of a solar power supply circuit using the LM317T voltage regulator. The goal of this project is to develop a reliable 12V output power supply for our device, utilizing solar energy as the primary power source.

## Project Overview

### Components

The power supply circuit includes the following components:

| Comment            | Description                                                                                  | Designator | Footprint     | LibRef                      | Quantity |
|--------------------|----------------------------------------------------------------------------------------------|------------|---------------|-----------------------------|----------|
| 0.1uF              | Ceramic Capacitor 100nF ±10% 50V X7R Radial                                                  | C1         | FP-RDE0M1-MFG | CMP-06035-051680-1          | 1        |
| Diode 1N4007       | 1 Amp General Purpose Rectifier                                                              | D1N4007    | DO-41         | Diode 1N4007                | 1        |
| Header 2           | Header, 2-Pin                                                                                | INPUT, OUTPUT | HDR1X2     | Header 2                    | 2        |
| 3310Y-001-202L     | Potentiometer Conductive Plastic 2k Power 0.25W Shaft Dia 0.125In 3310 Series | Bourns 3310Y-001-202L | POT RV1     | TRIM_3310Y-001-202L | 3310Y-001-202L            | 1        |
| 220                | AC01000006809JA100 Resistor, 68 Ohm, ± 5%, 1 W, Axial Leaded, Wirewound, General Purpose     | R2, R3     | RES_AC01_VIS  | CMP-00030-39747107-1        | 2        |
| SB350              | Diode Schottky 60V 3A Through Hole DO-201AD                                                  | schottky   | DIOAD1990W125L950D560 | SB350                      | 1        |
| LM317T             | 3-Terminal Adjustable Regulator, 3-pin TO-220                                                | VREG       | NDE0003A      | CMP-0062-02456-3            | 1        |

### Circuit Description

The solar power supply circuit is designed to provide a stable 12V output for powering our device. The circuit utilizes the LM317T voltage regulator to ensure a consistent output voltage, even with variations in the input from the solar panels.

Key components and their functions in the circuit include:

- **LM317T Voltage Regulator:** A versatile adjustable voltage regulator that allows us to set the desired output voltage (12V in this case) using external resistors.
- **1N4007 Diode:** Used to protect the circuit from potential reverse polarity.
- **Ceramic Capacitor (0.1uF):** Used for filtering and stabilizing the voltage supply.
- **Potentiometer (3310Y-001-202L):** Allows for fine adjustment of the output voltage.
- **Resistors (68 Ohm):** Used in conjunction with the potentiometer to set the output voltage of the LM317T.
- **Schottky Diode (SB350):** Ensures efficient power rectification with low forward voltage drop, which is crucial for minimizing losses in solar power applications.
- **Headers (2-Pin):** Used for input and output connections.

### PCB Design - Schematic 

![Solar Power Supply schematic](https://github.com/uvinduuu/Nexify-Adaptive-Traffic-Control-System/blob/main/PCB%20Design/solarPWschematic.png)

### PCB Design - PCB Layout

![Solar Power Supply - pcb layout](https://github.com/uvinduuu/Nexify-Adaptive-Traffic-Control-System/blob/main/PCB%20Design/solarPWpcb.png)

### PCB Design - PCB 3D View

![Solar Power Supply - pcb 3D view](https://github.com/uvinduuu/Nexify-Adaptive-Traffic-Control-System/blob/main/PCB%20Design/solarPW3D.png)
