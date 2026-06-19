# Hadamard Test

This folder contains the implementation of the Hadamard Test using Qiskit.

## Objective

The Hadamard Test is a quantum algorithm used to estimate the expectation value of a unitary operator. In this implementation, a controlled phase gate is used and the estimation error is analyzed as a function of the number of measurement shots.

## Files

* `Hadamard_good.ipynb` : Jupyter notebook containing the implementation and simulation.
* `hadamard_test_error_vs_shots.png` : Error analysis plot showing the scaling of estimation error with the number of shots.

## Tools Used

* Python
* Qiskit
* Qiskit Aer Simulator
* NumPy
* Matplotlib

## Result

The error decreases approximately as ( O(1/\sqrt{N}) ), consistent with the expected statistical behavior of quantum measurements.
