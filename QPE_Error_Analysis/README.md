\# Quantum Phase Estimation (QPE) Error Analysis



This folder contains an implementation of the Quantum Phase Estimation (QPE) algorithm using Qiskit, along with an analysis of the estimation error as a function of the number of measurement shots and the number of ancilla qubits.



\## Objective



The objective is to estimate the phase θ of a Phase Gate using the Quantum Phase Estimation (QPE) algorithm and study:



\- Error vs Number of Shots

\- Error vs Number of Ancilla Qubits



for the phase values:



\- θ = 0.5625

\- θ = 0.1234



\## Files



\* `QPE\_Error\_Analysis.ipynb` : Jupyter notebook containing the implementation and simulations.

\* `qpe\_error\_vs\_shots.png` : Error versus number of measurement shots.

\* `qpe\_error\_vs\_ancilla.png` : Error versus number of ancilla qubits.



\## Tools Used



\* Python

\* Qiskit

\* Qiskit Aer Simulator

\* NumPy

\* Matplotlib



\## Results



\### Error vs Number of Shots



!\[Error vs Shots](qpe\_error\_vs\_shot.png)



For a fixed ancilla register size (4 qubits), increasing the number of measurement shots does not significantly reduce the phase estimation error.



The dominant source of error is the finite precision of the ancilla register rather than statistical sampling noise. Consequently, the error remains approximately constant as the number of shots increases.



The theoretical convergence rate for QPE is:



O(1/N)



where N is the number of measurement shots.



\### Error vs Number of Ancilla Qubits



!\[Error vs Ancilla](qpe\_error\_vs\_ancilla.png)



The phase estimation error decreases as the number of ancilla qubits increases.



For θ = 0.5625, the error becomes essentially zero when four ancilla qubits are used because the phase has an exact 4-bit binary representation (0.1001₂).



For θ = 0.1234, the error decreases significantly but remains finite because the phase cannot be represented exactly using a finite number of binary digits.



These results demonstrate that the accuracy of Quantum Phase Estimation is primarily determined by the number of ancilla qubits, which control the phase resolution of the algorithm.



\## Conclusion



The QPE algorithm successfully estimates the phase of the unitary operator. The error analysis shows that increasing the number of ancilla qubits improves the estimation precision, while increasing the number of shots alone cannot overcome the finite-resolution limitation imposed by the ancilla register.



\## References



\- Qiskit Documentation

\- M. A. Nielsen and I. L. Chuang,

&#x20; \*Quantum Computation and Quantum Information\*

\- Course Notes: Scientific Computing with Quantum Algorithms (DS 394),

&#x20; Prof. Phani Motamarri, CDS Department, Indian Institute of Science (IISc), Bangalore

