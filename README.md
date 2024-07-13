# Quantum Computing with Qiskit 🚀

This repository contains a series of Jupyter notebooks that demonstrate various quantum computing concepts using Qiskit. Each notebook focuses on a specific topic and provides code examples and explanations to help you understand and implement quantum algorithms.

## Notebooks 📚

1. **1-fist-steps.ipynb**: 🧑‍🏫 Introduction to quantum computing with Qiskit. This notebook covers the basics of creating a quantum circuit with one qubit and one classical bit, simulating the circuit, and visualizing the results.

2. **2-multiple-qubits.ipynb**: 🔗 Working with multiple qubits. This notebook demonstrates how to create a quantum circuit with two qubits and two classical bits, apply quantum gates, and simulate the circuit using statevector and qasm simulators.

3. **3-Pauli-x-gate.ipynb**: ❌ Exploring the Pauli-X gate. This notebook shows how to create a quantum circuit with one qubit, apply the Pauli-X gate, and visualize the statevector and Bloch multivector.

4. **4-hadamard-gate.ipynb**: 🎩 Applying the Hadamard gate. This notebook demonstrates how to create a quantum circuit with one qubit, apply the Hadamard gate, and visualize the statevector and Bloch multivector.

5. **5-phase-shift.ipynb**: 🔄 Exploring phase shift gates in quantum circuits. This notebook demonstrates how to create quantum circuits with three qubits, apply various quantum gates, and visualize the resulting statevector and Bloch multivector. Additionally, it covers the use of parameterized rotation gates and includes a challenge section where a quantum circuit is simulated using the qasm simulator, and the results are visualized with a histogram.

6. **6-multiqubit-gates.ipynb**: 🛠️ Exploring multi-qubit gates in quantum circuits. This notebook demonstrates the use of various multi-qubit gates including the CNOT, CCNOT (Toffoli), SWAP, and Fredkin (CSWAP) gates. It includes the creation of quantum circuits with three qubits, application of these gates, and visualization of the resulting statevector and Bloch multivector. Additionally, there is a challenge section that implements logic XOR and AND operations, with results measured and visualized.

7. **7-quantum-entanglement.ipynb**: 🔗 Investigating quantum entanglement and Bell states. This notebook demonstrates the creation of Bell states using a two-qubit quantum circuit, the application of Hadamard and CNOT gates, and the visualization of the resulting statevector and measurement results using histograms. Additionally, it includes a challenge section to create and analyze a GHZ state with a three-qubit circuit, as well as another challenge to explore further entanglement properties with a two-qubit circuit.

8. **8-ibm-quantum-computer-run.ipynb**: ☁️ Running quantum circuits on IBM Quantum Computers. This notebook demonstrates how to create and simulate a quantum circuit on a local qasm simulator, then run the same circuit on IBM's quantum hardware. It includes steps for loading an IBM API key, using the Qiskit Runtime Service, and monitoring jobs. The notebook also illustrates how to visualize the results with histograms and discusses the impact of noise and decoherence on real quantum computations.

9. **9-quantum-algorithms.ipynb**: 🧩 Exploring quantum algorithms with Qiskit. This notebook covers two significant quantum algorithms: Superdense Coding and Quantum Teleportation. It demonstrates the creation and execution of these algorithms using quantum circuits. For Superdense Coding, the notebook shows how to encode and transmit two classical bits using a single qubit by leveraging entanglement. For Quantum Teleportation, it details the process of transmitting a qubit's state using entangled qubits and classical communication. The results are visualized using statevector and histogram plots, illustrating the effectiveness and outcomes of these algorithms.

## Requirements 🛠️

- Qiskit
- Matplotlib
- Pylatexenc

You can install the required packages using the following command:

```bash
pip install -r requirements.txt
```