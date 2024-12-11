FSM Door Controller
Finite State Machine (FSM) for Automatic Door Control Systems.

Project Overview
This project implements three FSM designs for automatic door control:

Moore FSM: Outputs depend only on the current state, ensuring stable operation.
Mealy FSM (Combinational Outputs): Outputs depend on both the current state and inputs, offering quicker response.
Mealy FSM (Synchronous Outputs): Combines the advantages of fast response and stable outputs synchronized to the clock.
The FSMs are developed for VHDL-based hardware implementation, enabling reliable and efficient deployment in embedded systems.

Features
State Transitions: Includes well-defined transitions for states such as Open, Closed, Locked, and Error.
Input Handling: Supports multiple inputs (e.g., switches and buttons) to control state changes.
Output Indicators: LEDs reflect system states and error conditions in real time.
Testbench Validation: Rigorous simulation testing with waveform analysis in ModelSim.
File Structure
src/: VHDL source files for all three FSM designs.
doc/: Documentation including design specifications and simulation results.
simulation/: Testbenches, simulation logs, and waveform images.
How to Use

Clone the repository:

bash
git clone https://github.com/your_username/FSM_Door_Controller.git

Open the project in Quartus Prime or ModelSim.
Compile the VHDL files and run the provided testbenches for verification.
Deploy the FSM designs on an FPGA board to validate functionality.
