# EcoChip: Optimizing Energy Efficiency in System-on-Chip Designs

## Overview
EcoChip is a simulation project aimed at optimizing the energy efficiency of System-on-Chip (SoC) designs. The project focuses on managing buffer sizes, arbiter weights, and power consumption thresholds to achieve optimal performance while minimizing energy consumption.

## Simulation Code
The main simulation code is written in MATLAB and simulates the behavior of the SoC components over a specified number of timesteps. Key parameters such as buffer sizes, arbiter weights, and power thresholds are defined at the beginning of the code.

## Simulation Workflow
1. **Parameters Definition**: Define the parameters such as buffer sizes, arbiter weights, and power thresholds.
2. **Simulation Loop**: Iterate over a specified number of timesteps and execute CPU operations, IO operations, and arbiter logic in each timestep.
3. **Power Management**: Monitor power consumption and apply throttling if necessary to maintain power consumption below the threshold.

## Function Definitions
- **cpu_operations**: Implements CPU operations.
- **io_operations**: Implements IO operations.
- **arbiter_operations**: Implements arbiter logic.
- **apply_throttling**: Applies throttling based on power threshold.

## Usage
To run the simulation:
1. Open MATLAB.
2. Copy and paste the provided code into a new MATLAB script file.
3. Run the script to execute the simulation.

## Contributions
Contributions to the EcoChip project are welcome! If you have ideas for improving energy efficiency in SoC designs or want to contribute code enhancements, feel free to submit a pull request.


Feel free to modify and expand upon this README template as needed for your project!
![Image](https://github.com/eesha2501/EcoChip/assets/121451707/0b133c52-93b6-472b-995e-2fbf94ea31c0)
