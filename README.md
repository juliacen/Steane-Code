# Steane's Code Under Random Pauli Error Channel

This repository contains a Jupyter notebook that demonstrates the construction and simulation of **Steane's quantum error-correfcting [[7,1,3]] code**. The notebook applies random Pauli X,Y or Z error with probability p to each qubit in the encoded quantum states and explores how Steane's code detects and corrects these errors, evaluating the overall success probability with Qiskit's AerSimulator.

## Introduction

One of the major challenges faced in quantum computation is how susceptible quantum states are to errors, for example, from interactions with the environment. The **Steane's code**, developed in 1996, is one of the earliest and most well-known examples of a **Calderbank–Shor–Steane (CSS)** quantum code. It is constructed using the classical [7,4,3] Hamming code and is able to detect and correct a single physical qubit.

## Contents of Notebook

### 1. What is the Steane's Code?
A brief overview of quantum error correction and Steane's code.

### 2. Building Steane's Code
- **Encoding states**
    Encode an arbitrary quantum state defined by a Boolean string of length n         to a logical state for Steane's code.
- **Simulating Noise**
    Design a circuit to simulate a Pauli error noise channel
- **Error Detection**
    Create a syndrome extractor to identify single qubit errors
- **Error Correction and Decoding**
    Correct and recover physical qubits to see performance of Steane's code

### 3. Success Probability
Run simulations with Qiskit's AerSimulator for Steane's code to see how it performs for a range of error probabilties, p.
