\# Quantum Fourier Transform (QFT) and Inverse QFT (IQFT)



\## Overview



This notebook implements the Quantum Fourier Transform (QFT) and its inverse (IQFT) from scratch using Qiskit.



The Quantum Fourier Transform is an important quantum algorithm used in several quantum applications such as:

\- Quantum Phase Estimation (QPE)

\- Quantum algorithms involving frequency analysis



\## Implementation



The QFT circuit is constructed using:



\- Hadamard gates

\- Controlled phase rotation gates

\- Swap operations for qubit reversal



The inverse QFT is implemented by:



\- Reversing swap operations

\- Applying inverse controlled phase rotations

\- Applying Hadamard gates



\## Tools Used



\- Python

\- Qiskit

\- Qiskit Aer

\- NumPy



\## Results



\### Quantum Fourier Transform Circuit



!\[QFT Circuit](qft\_circuit.png)





\### Inverse Quantum Fourier Transform Circuit



!\[IQFT Circuit](iqft\_circuit.png)





\## Conclusion



The implementation demonstrates the construction of QFT and IQFT circuits using basic quantum gates in Qiskit.

