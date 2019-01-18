# Learning Qiskit: Guided exercises for developers
Jupyter notebooks containing guided exercises for developers learning quantum computing with Qiskit.

## Instructions
These notebooks may be run in the cloud, or downloaded and run locally. 
**Note:** *When running in the cloud environments mentioned here, using a Chromium-based broswer such as Chrome or Brave is strongly recommended*

**To run in Google Colaboratory (in the cloud):** Ensure that you have a Google account, and navigate to your desired notebook in this repository. Click the **Open in Colab** icon at the top the notebook.
Note: Uncommenting the **!pip install qiskit** in the first cell in each of the notebooks installs Qiskit into the user's Colaboratory environment, so there is a bit of a delay and lots of output during this process.

**To run locally:** Clone or download this repository, and install the Qiskit foundational libraries in a Python environment using the instructions on the [Qiskit Terra site](https://qiskit.org/terra).

## Guided exercises (recommended to do in this order)
#### [The quantum version of a NOT gate](./quantum_not_gate_qiskit.ipynb)
This guided exercise is an introduction to creating a single-wire quantum circuit using Qiskit, and to the Pauli-X gate. It also introduces *qubits*, including various ways to represent and visualize them. 

#### [Flipping a coin quantumly](./quantum_coin_flipping.ipynb)
This guided exercise introduces the Hadamard gate, quantum superpositions, probability amplitudes, and measurement probabilities. It also serves as a gentle introduction to Dirac notation.

#### [Multi-qubit quantum circuits](./multi_qubit_circuits.ipynb)
This guided exercise builds on the previous one by creating circuits with multiple qubits, and examining their quantum state vectors. It also demonstrates how quantum states may be visualized.

#### [Entangling qubits with a CNOT gate](./entangling_qubits.ipynb)
This guided exercise introduces the idea of quantum entanglement, and explores the four Bell states.

## Troubleshooting Guide
Here are some common issues and their resolutions
<table>
    <tr>
        <th>Symptom</th>
        <th>What to do</th>
    </tr>
    <tr>
        <td>Cell contains an error message that contains ChangedInMarshmallow3Warning</td>
        <td>Not a problem, but re-run the cell to make it disappear</td>
    </tr>
</table>
