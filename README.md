# quantum-algorithms-qiskit
Qiskit-based implementations of quantum computing algorithms for academic assignments.

# Qiskit Algorithms Assignment

## Question: Quantum Phase Estimation (QPE)

### Implementation
This solution implements QPE using:
- Controlled phase rotations
- Inverse Quantum Fourier Transform
- Aer simulator

### Tools
- Qiskit
- Python

### Output
Measurement histogram shows the estimated phase distribution.

# Grover’s Algorithm for Letter Search Problem

This assignment implements Grover’s algorithm to find occurrences of specific letters ('a', 'b', 'c', 'd') in a randomly generated string.

## Problem Statement

Given a random string, we use Grover's algorithm to amplify probability of finding positions of specific letters.

## Oracle Design

The oracle marks indices where the target letter appears using X gates and multi-controlled Z gate (MCMT).

## Grover Operator

We construct Grover operator using Qiskit and apply optimal iterations based on:

## Results

We estimate probability of occurrence of letters using repeated Grover simulations.


