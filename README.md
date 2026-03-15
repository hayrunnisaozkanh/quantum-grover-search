# quantum-grover-search
Grover algorithm simulation using Qiskit

# Quantum Grover Search Algorithm Simulation

## About
This notebook explains Grover's Search Algorithm step by step. It uses both classical and quantum computing to search for a marked element in a list, and compares the results. For the quantum computing part, it implements Grover's Search Algorithm, where the target state is |11⟩.

## Motivation
I prepared this notebook to explain the basics of Grover's Search Algorithm. I also aimed to improve myself for future studies, as an LL.M. candidate in Information and Technology Law at the Social Sciences University of Ankara, with a research focus on quantum computing and law. Additionally, this is my first attempt to write a Qiskit notebook with explanations.

## Structure: 
- **Theoretical information:** A brief introduction to Grover's Search Algorithm step by step. 
- **Classical computing simulation:** Finding a marked element in a list using classical computing
- Visualization of classical steps: Bar plots of classical computing steps
- **Implementation of quantum computing:** Modelling of the oracle and the diffusion operator. Firstly, flipping the sign of the state of the marked element. Secondly, by inversion about the mean, amplifying the amplitudes.
- **Results:** Amplitude amplification of the target state is demonstrated through quantum circuit simulation.

## Requirements
- Python
- Qiskit
- Qiskit-Aer
- Matplotlib
- NumPy

## Result
In the classical computing part, we searched for 7, which is the marked element of the chosen list. In the  quantum computing part, we got the |11⟩in just one iteration with 100% probability. Complexity is decreased from O(N) to O(√N).

## Author
Hayrunnisa Özkan
LL.M. Candidate in Information and Technology Law at the Social Sciences University of Ankara

March 2026
