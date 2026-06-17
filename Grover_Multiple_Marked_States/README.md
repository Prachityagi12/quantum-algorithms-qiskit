\# Grover's Algorithm with Multiple Marked States



\## Problem Statement



Implement Grover's search algorithm using Qiskit to identify multiple marked states in a 3-qubit search space.



The marked states are:



\* |011⟩

\* |100⟩



\## Methodology



1\. Construct a quantum oracle that marks the target states.

2\. Build the Grover operator using the oracle.

3\. Determine the optimal number of Grover iterations.

4\. Execute the circuit on the Qiskit Aer simulator.

5\. Measure the output state distribution.



\## Tools Used



\* Python

\* Qiskit

\* NumPy

\* Qiskit Aer

\* Matplotlib



\## Results



The measurement outcomes are concentrated on the marked states:



| State | Counts |

| ----- | ------ |

| 011   | 5091   |

| 100   | 4909   |



All other states were measured with negligible probability.



\### Output Histogram



!\[Grover Search Results](grover\_multiple\_solutions\_histogram.png)



\## Conclusion



The results demonstrate successful amplitude amplification of the marked states using Grover's search algorithm.



