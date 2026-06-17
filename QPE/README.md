\# Quantum Phase Estimation (QPE)



\## Problem Statement



Implement the Quantum Phase Estimation (QPE) algorithm using Qiskit to estimate the phase of an eigenvalue of a unitary operator.



The implementation uses a 3-qubit counting register and 1 eigenstate qubit.



\---



\## Methodology



The algorithm consists of the following steps:



1\. Apply Hadamard gates on counting qubits to create superposition.



2\. Prepare the eigenstate of the unitary operator.



3\. Apply controlled phase rotation operations.



4\. Apply the inverse Quantum Fourier Transform (IQFT).



5\. Measure the counting qubits to estimate the phase.



\---



\## Tools Used



\- Python

\- Qiskit

\- Qiskit Aer Simulator

\- NumPy

\- Matplotlib



\---



\## Results



The circuit was simulated using 10000 shots.



Measurement counts:



| State | Counts |

|------|--------|

| 000 | 155 |

| 001 | 325 |

| 010 | 1747 |

| 011 | 6876 |

| 100 | 452 |

| 101 | 194 |

| 110 | 131 |

| 111 | 120 |



The highest probability measurement is obtained for state: 011




which corresponds to the estimated phase output of the QPE algorithm.



\---



\## Output Visualizations



\### QPE Circuit



!\[QPE Circuit](qpe\_circuit.png)





\### Transpiled QPE Circuit



!\[Transpiled QPE Circuit](qpe\_transpiled\_circuit.png)





\### Measurement Histogram



!\[QPE Histogram](qpe\_histogram.png)





\---



\## Conclusion



The QPE algorithm successfully estimates the phase of the given unitary operator. The measurement distribution shows maximum probability around the expected phase state.

