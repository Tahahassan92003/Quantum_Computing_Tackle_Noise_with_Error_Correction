# Tackle Noise with Error Correction
 This project will explore quantum error correction using the repetition code from Qiskit's guide. We will encode information across multiple qubits to detect and correct bit-flip errors, implement the code in Qiskit, test error resilience, and analyze performance, providing foundational insights for advanced error correction techniques.

## Table of Contents

- [Motivation](#Motivation)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#Features)
- [Collaborators](#Collaborators)
- [Contribute](#Contribute)

## Motivation:

Quantum computing promises to revolutionize industries by solving problems that classical computers cannot. However, one of the biggest challenges in scaling quantum systems is the presence of noise and errors that arise due to imperfect hardware. These errors can quickly corrupt quantum computations, leading to unreliable results. My motivation for building this project stemmed from the desire to contribute to overcoming this critical issue. By exploring quantum error correction, specifically using repetition codes, I aimed to better understand how noise affects quantum computations and how we can protect quantum information to make quantum computers more resilient.

Why did I build this project?

I built this project because quantum computing is still in its early stages, and to make it practical for real-world applications, we need robust error correction techniques. Quantum error correction is a fundamental building block that will allow us to scale quantum systems beyond a handful of qubits. We wanted to explore the implementation of a simple but effective error correction code—the repetition code—to understand the trade-offs between error correction complexity and its ability to protect against noise. This project not only enhances my understanding of quantum error correction but also contributes to the field by experimenting with noise resilience techniques.

What problem does it solve?

This project addresses the problem of error susceptibility in quantum systems, which is a significant barrier to building reliable and scalable quantum computers. Specifically, the repetition code implementation in this project helps detect and correct bit-flip errors which is a common form of quantum noise. By simulating error correction methods, this project provides a solution that ensures quantum computations remain accurate despite noisy conditions, making quantum computing more feasible for practical use.

What did we learn?

Through this project, I learned the importance of quantum error correction in maintaining the integrity of quantum computations in noisy environments. I gained hands-on experience with quantum simulation tools like Qiskit and understood the process of encoding logical qubits across multiple physical qubits. I also learned the limitations of simple error correction methods like repetition codes and the potential benefits of more complex techniques. This project taught me how to evaluate error correction effectiveness through simulations and how the size of the code impacts the system’s resilience to noise. Ultimately, I learned that error correction is crucial for scaling quantum computing, and it provides a foundation for exploring more advanced fault-tolerant techniques.

## Installation

git clone https://github.com/Tahahassan92003/Tackle_Noise_with_Error_Correction

Install dependencies on Collab:

!pip install qiskit==0.37.2

Install dependencies on Vs_Code:

pip install qiskit==0.37.2

## Usage
If using the Notebook run cells in order, to simulate the encoding, decoding process, Run the last cell for a real world sample problem.

## Features
1. Noise Model Simulation: Custom noise models based on Pauli and depolarizing errors with configurable error rates.
2. Repetition Code Implementation: Usage of the RepetitionCode class to create quantum circuits for logical qubits with 
   specified code distances.
3. Simulation and Execution: Execution of circuits on quantum simulators, noise models, and real quantum hardware (IBM 
   Quantum devices).
4. Error Detection and Correction: Handling of errors with a majority voting mechanism to ensure correct results after noise 
   interference.
5. Decoding Techniques: Usage of the GraphDecoder and LookupTableDecoding methods for processing and correcting errors.

## Collaborators

https://github.com/AsadNoorKhan

## Contribute

Contributions are encouraged! Feel free to open an issue or submit a pull request with your proposed changes.

