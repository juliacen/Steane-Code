# Steane's Code Under Random Pauli Error

This repository contains a Jupyter notebook that demonstrates the construction and simulation of **Steane's** quantum error-correfcting, [[7,1,3]] code. The notebook applies random Pauli X,Y or Z error with probability (\ p\leq 3 \) to encoded quantum states and explores how Steane's code detects and corrects these errors, estimating the overall success probability.

## Overview

Quantum computing systems are prone to decoherence and operational errors. The **Steane code**, developed in 1996, is one of the earliest and most well-known examples of a **Calderbank–Shor–Steane (CSS)** quantum code. It is constructed using classical [7,4,3] Hamming codes and protects a single logical qubit using 7 physical qubits.

The notebook is divided into the following sections:

### 1. What is the Steane's Code?
A brief overview of quantum error correction and the theory behind the Steane code.

### 2. Building Steane's Code
- **The Code Structure**: Description of stabilizer generators and logical states
- **Encoding |x⟩**: Encoding process for arbitrary single-qubit states
- **Simulating Noise**: Application of random Pauli (X, Y, Z) errors
- **Error Detection**: Syndrome extraction to identify error patterns
- **Error Correction and Decoding**: Recovery of logical states

### 3. Success Probability
Numerical estimation of how well the Steane code performs against random single-qubit errors.
