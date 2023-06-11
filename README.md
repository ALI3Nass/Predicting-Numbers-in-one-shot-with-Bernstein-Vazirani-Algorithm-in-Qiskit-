# Predicting Numbers in one shot with Bernstein-Vazirani Algorithm in Qiskit

This repository contains an example of predicting numbers in one shot using the Bernstein-Vazirani algorithm implemented in Qiskit, a Python framework for working with quantum circuits and simulating quantum systems. The code snippet provided demonstrates how to construct a quantum circuit and apply the Bernstein-Vazirani algorithm to predict a secret number.

## Installation

To run the code in this repository, make sure you have Qiskit installed. You can install Qiskit using the following command:
pip install qiskit


## Usage

The code snippet provided can be run in a Jupyter Notebook or any Python environment. The code implements the Bernstein-Vazirani algorithm to predict a secret number. Here's a breakdown of the code:

- **Creating a Quantum Circuit**: Demonstrates how to create a quantum circuit with 7 qubits and 6 classical bits using Qiskit and visualize it.
- **Applying Quantum Gates**: Applies quantum gates, such as the Hadamard gate and CNOT gate, to the qubits in the circuit.
- **Adding Barriers**: Inserts barriers in the circuit to separate different stages of the computation.
- **Implementing Bernstein-Vazirani Algorithm**: Implements the Bernstein-Vazirani algorithm to predict the secret number provided.
- **Measuring Qubits**: Measures qubits in the circuit and assigns the measurement results to classical bits.
- **Simulating with QASM Simulator**: Simulates the quantum circuit using the QASM simulator backend and obtains the measurement counts.
- **Printing the Result**: Prints the measurement counts as the predicted secret number.

Feel free to explore and modify the code snippet to experiment with quantum computing concepts and the Bernstein-Vazirani algorithm using Qiskit.

## Contributing

If you would like to contribute to this repository, feel free to submit a pull request. Contributions, improvements, and bug fixes are always welcome!

## License

This repository is licensed under the [MIT License](LICENSE).
