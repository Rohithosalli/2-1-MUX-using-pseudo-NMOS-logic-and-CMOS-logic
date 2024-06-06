# 2-1 Multiplexer using Pseudo-NMOS Logic and CMOS Logic

This project demonstrates the design and simulation of a 2-to-1 multiplexer (MUX) using both Pseudo-NMOS logic and CMOS logic. The design and simulations were carried out using the Cadence Virtuoso environment.

## Table of Contents
- [Introduction](#introduction)
- [Design Overview](#design-overview)
- [Pseudo-NMOS Logic](#pseudo-nmos-logic)
- [CMOS Logic](#cmos-logic)
- [Schematics](#schematics)
- [Simulation Results](#simulation-results)
- [Conclusion](#conclusion)
- [Acknowledgements](#acknowledgements)
- [License](#license)

## Introduction
A multiplexer is a combinational circuit that selects one of the many input signals and directs it to the output. The 2-to-1 MUX selects one of the two inputs based on a single control signal. This project explores two implementations of the 2-to-1 MUX: one using pseudo-NMOS logic and the other using CMOS logic.

## Design Overview
### Pseudo-NMOS Logic
Pseudo-NMOS logic uses a combination of NMOS transistors and a weak PMOS transistor that is always on. This approach is known for its simplicity and speed but consumes static power.

### CMOS Logic
CMOS logic uses both PMOS and NMOS transistors to implement the logic gates. It is known for its low power consumption and high noise immunity.

## Schematics
Below are the schematics of the 2-to-1 MUX using both Pseudo-NMOS logic and CMOS logic:

### Pseudo-NMOS Logic Schematic
![Pseudo-NMOS Logic] <img src=https://github.com/Rohithosalli/2-1-MUX-using-pseudo-NMOS-logic-and-CMOS-logic/blob/main/sudonmos_mu.jpg?raw=true>

### CMOS Logic Schematic
![CMOS Logic]<img src="https://github.com/Rohithosalli/2-1-MUX-using-pseudo-NMOS-logic-and-CMOS-logic/blob/main/coms%20mu.jpg?raw=true">

### Pseudo-NMOS Logic Test Schematic
![Pseudo-NMOS Logic Test](C:\Users\rohit\OneDrive\Pictures\test_sudo.jpg)

### CMOS Logic Test Schematic
![CMOS Logic Test]<img src="https://github.com/Rohithosalli/2-1-MUX-using-pseudo-NMOS-logic-and-CMOS-logic/blob/main/test_cmos.jpg?raw=true">

## Simulation Results
The simulation results demonstrate the functionality and performance of both implementations. The key parameters analyzed include power consumption, delay, and noise margins.

### Pseudo-NMOS Logic Simulation Results
![Pseudo-NMOS Simulation Results]<img src="https://github.com/Rohithosalli/2-1-MUX-using-pseudo-NMOS-logic-and-CMOS-logic/blob/main/graph_sudo.jpg?raw=true">

### CMOS Logic Simulation Results
![CMOS Simulation Results] <img src="https://github.com/Rohithosalli/2-1-MUX-using-pseudo-NMOS-logic-and-CMOS-logic/blob/main/graph_cmos.jpg?raw=true">

## Conclusion
The pseudo-NMOS logic provides a faster response at the cost of higher static power consumption, whereas the CMOS logic offers lower power consumption with reliable performance. The choice between these two implementations depends on the specific application requirements.

## Acknowledgements
This project was carried out using the Cadence Virtuoso software suite, and I give special thanks to the guidance and support from the faculty and peers.

## License
This project is licensed under the MIT License. Please take a look at the [LICENSE](LICENSE) file for more details.
