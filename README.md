# Steane's Code Under Random Pauli Error

**Author**: Julia Cen

This repository contains a Jupyter notebook that demonstrates the construction and simulation of the **Steane Code**, a foundational [[7,1,3]] quantum error-correcting code. The notebook applies random Pauli errors to encoded quantum states and explores how Steane's code detects and corrects these errors, estimating the overall success probability.

## 📘 Overview

Quantum computing systems are prone to decoherence and operational errors. The **Steane code**, developed in 1996, is one of the earliest and most well-known examples of a **Calderbank–Shor–Steane (CSS)** quantum code. It is constructed using classical [7,4,3] Hamming codes and protects a single logical qubit using 7 physical qubits.

This notebook provides:

- A conceptual introduction to Steane’s code
- A complete simulation framework for encoding, introducing noise, detecting and correcting errors
- Analysis of the code's success probability under random single-qubit Pauli errors

## 🧪 Contents

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

### 4. References
Foundational papers and online resources for further reading.

## ⚙️ Requirements

To run the notebook, you’ll need:

- Python 3.7+
- Jupyter Notebook or JupyterLab
- `numpy`
- `qiskit` (if using actual quantum circuit implementations)
- `matplotlib` (for visualizations, if included)

Install dependencies with:

```bash
pip install numpy qiskit matplotlib
```

## 🚀 Getting Started

1. Clone the repository:

```bash
git clone https://github.com/yourusername/steane-code-simulation.git
cd steane-code-simulation
```

2. Launch the notebook:

```bash
jupyter notebook SteaneCode.ipynb
```

## 📚 References

1. Steane, A. (1996). *Error Correcting Codes in Quantum Theory*. Phys. Rev. Lett. 77(5).
2. Nakahara, M., & Ohmi, T. (2008). *Quantum Computing: From Linear Algebra to Physical Realizations*. CRC Press.
3. [QECFT Blog on Stabilizer Codes](https://abdullahkhalid.com/qecft/stabilizer-codes/encoding-circuits-for-stabilizer-codes/)
