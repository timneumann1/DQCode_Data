This repository contains all optimisation and simulation data produced in the DQCode project. 

> [!NOTE]
> The simulation data column `avg_fidelity` has been computed as the average overlap of corrected state and target state, instead of the average fidelity (squared overlap). This has been fixed in the codebase; however, these two metrics actually coincide for the experiments at hand, since the circuit-level noise and Pauli corrections cannot induce a non-Pauli logical error at the end of the circuit.
