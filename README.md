Here's a README file for your quantum random number generator project repository:

# Quantum Random Number Generator (QRNG)

This repository contains the implementation and analysis of a quantum random number generator using IBM's quantum computers.

## Project Overview

We developed a simple quantum random number generator using Hadamard gates applied to 100 qubits initialized in the |0⟩ state. The project includes the following components:

- QRNG implementation
- Data analysis using Principal Component Analysis (PCA) and Fast Fourier Transform (FFT)
- Entropy calculation and randomness tests
- Error analysis and mitigation strategies

## QRNG Implementation

The core of our QRNG consists of:

1. Initialization of 100 qubits in the |0⟩ state
2. Application of Hadamard gates to all qubits
3. Measurement of all qubits
4. Recording of measurement results in classical registers

## Data Analysis

We performed extensive analysis on the generated data:

- Attempted classification using neural networks (results were inconclusive)
- Applied PCA to identify major sources of error and bias
- Used FFT for frequency analysis
- Calculated fidelity using density matrices

## Randomness Tests

We employed several tests to evaluate the randomness of our QRNG:

- Shannon entropy calculation
- Compressibility test
- P-value analysis
- Hashing algorithm for post-processing

## Error Analysis

We investigated various sources of error in our QRNG:

- Identified qubits prone to noise through multiple runs
- Analyzed decoherence times (T1 and T2), SX Error, and Readout time error
- Compared results across different IBM quantum devices

## Future Improvements

Based on our findings, we propose the following improvements:

1. Implement bias mitigation techniques based on PCA results
2. Develop adaptive algorithms to avoid noisy qubits
3. Explore more advanced post-processing techniques to increase entropy

## Requirements

- Qiskit
- NumPy
- SciPy
- Matplotlib
- Pandas

## Usage

(Include instructions on how to run your QRNG and analysis scripts)

## Contributors

(List the names of project contributors)

## License

(Specify the license under which this project is released)

## Acknowledgments

We would like to thank IBM for providing access to their quantum computers through the IBM Quantum Experience platform.
