# Smart Automotive Cabin Controller (BCM_ECU)

## Overview

The Smart Automotive Cabin Controller is a microcontroller-based Body Control Module (BCM) project designed and documented using Proteus Design Suite. The project schematic includes an STM32F103C8 microcontroller and peripheral components associated with vehicle body-control functions.

The project focuses on the representation of automotive cabin-control components and their integration within a microcontroller-based system.

## Features and Components

- **Microcontroller:** STM32F103C8.
- **Door Status Indication:** Includes a door-lock status indicator.
- **Seat-Belt Warning:** Includes a sounder component associated with seat-belt warning functionality.
- **Lighting Components:** Includes lamp and LED components.
- **Input Components:** Includes push-button components for control inputs.
- **Proteus Design:** Provides a schematic-based representation of the BCM system.

These features describe components identified in the Proteus project; their complete functional behavior must be confirmed through simulation and firmware testing.

## Technologies and Tools

- Proteus Design Suite — circuit design and simulation.
- STM32F103C8 — microcontroller specified in the schematic.
- STM32CubeIDE — firmware development environment referenced by the project configuration.

## Project Structure

The supplied Proteus project archive contains the following files:

- `ROOT.DSN` — schematic and design data.
- `ROOT.CDB` — component and design database.
- `PROJECT.XML` — project metadata.
- `FIRMWARE.XML` — firmware configuration metadata.
- `SCRIPTS/PWRRAILS.DAT` — power-rail definitions.

## How to Open the Project

1. Install a compatible version of Proteus Design Suite.
2. Clone or download this repository.
3. Open `BCM_ECU.pdsprj` in Proteus.
4. Verify that the schematic and all required dependencies are available.
5. Check the firmware configuration and confirm that the required firmware file is accessible.
6. Run the simulation and observe the circuit behavior.

## OUTPUT:

<img width="1556" height="874" alt="image" src="https://github.com/user-attachments/assets/f65992ed-970e-4589-9210-2d080a2b7dbf" />


## Verification Status

The Proteus project archive and its schematic data have been inspected. Successful simulation, firmware execution, and individual feature tests have not yet been independently verified.

Simulation screenshots, test cases, and observed results should be added after testing the project in Proteus.

## Author

Nivesh N K
