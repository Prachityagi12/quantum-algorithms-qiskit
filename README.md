# Quantum Algorithms using Qiskit

This repository contains implementations and experiments of fundamental quantum algorithms using Qiskit.

The objective of this repository is to study and implement important quantum computing concepts including quantum search, quantum Fourier transform, and quantum phase estimation.

## Algorithms Implemented

### 1. Grover's Algorithm - Letter Search
Implementation of Grover's quantum search algorithm for searching a marked element from an unsorted search space.

Folder:
`Grover_Letter_Search`

---

### 2. Grover's Algorithm - Multiple Marked States
Extension of Grover's algorithm where multiple target states are marked and searched using amplitude amplification.

Folder:
`Grover_Multiple_Marked_States`

---

### 3. Quantum Fourier Transform (QFT) and Inverse QFT (IQFT)

Implementation of Quantum Fourier Transform (QFT) and its inverse operation (IQFT) using Qiskit.

QFT is a fundamental quantum operation used as a building block in various quantum algorithms, while IQFT is used for reversing the Fourier transformation and plays an important role in algorithms such as Quantum Phase Estimation.

Folder:
`QFT`

---

### 4. Quantum Phase Estimation (QPE)
Implementation of QPE algorithm for estimating phases of unitary operators.

Folder:
`QPE`

---

### 5. Hadamard Test

Implementation of the Hadamard Test for estimating the phase of a Phase Gate eigenvalue.

The project analyzes the estimation error as a function of the number of measurement shots and compares the observed convergence with the theoretical scaling.

Folder:
`Hadamard_Test`

---

### 6. Kitaev Phase Estimation

Implementation of Kitaev's Phase Estimation Algorithm using Qiskit.

The algorithm estimates the phase using a sequence of quantum circuits and classical post-processing, requiring fewer qubits than standard Quantum Phase Estimation.

Folder:
`Kitaev_Phase_Estimation`

---

### 7. Quantum Phase Estimation (QPE) Error Analysis

Error analysis of the Quantum Phase Estimation algorithm for different phase values.

The study investigates:

- Error vs Number of Shots
- Error vs Number of Ancilla Qubits

and compares the observed behavior with theoretical expectations.

Folder:
`QPE_Error_Analysis`

---

## Technologies Used

- Python
- Qiskit
- Qiskit Aer Simulator
- Jupyter Notebook

## Repository Structure

Each algorithm is implemented in a separate Jupyter notebook.

## Purpose

This repository serves as a collection of quantum algorithm implementations for learning and experimentation with quantum circuits and simulations.

## References

- Qiskit Documentation  
  https://qiskit.org/documentation/

- M. A. Nielsen and I. L. Chuang,  
  *Quantum Computation and Quantum Information*

- Course Notes: Quantum Computing (QT 207)  
  Prof. Navin Kashyap, ECE Department, Indian Institute of Science (IISc), Bangalore

- Course Notes: Scientific Computing with Quantum Algorithms (DS 394)   
  Prof. Phani Motamarri, CDS Department, Indian Institute of Science (IISc), Bangalore  
