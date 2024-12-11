# FSM Door Controller - Moore (Combinatory Outputs)

## Project Overview
This project implements a Finite State Machine (FSM) for door control using the Moore model. The design ensures that the outputs are combinatory and depend solely on the current state of the FSM. This approach guarantees predictable behavior, making it ideal for real-world applications such as automated door systems in commercial or industrial environments.

## Features
- **Moore Model**: The output logic is purely dependent on the current state of the FSM, ensuring clarity and simplicity in operation.
- **Combinatory Outputs**: The outputs are computed instantly as the state changes, without any delay from input fluctuations.
- **Robust Design**: The architecture minimizes metastability and ensures glitch-free operation.
- **Simulation-Tested**: Comprehensive simulations using ModelSim validate the FSM’s functionality under various scenarios.

## Applications
- Automated sliding doors in commercial spaces.
- Industrial gate control systems.
- Systems requiring simple and reliable state-based operations.

## File Structure
- **src/**: VHDL source files implementing the Moore FSM with combinatory outputs.
- **doc/**: Design documentation detailing the FSM states, transitions, and simulation results.
- **simulation/**: Includes simulation waveforms, test cases, and logs generated during validation.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/FSM_Door_Controller_Moore_Combinatory.git
