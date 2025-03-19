# Quantum-Circuit-Simulator-with-Interactive-Dashboard

This repository contains a "Quantum Circuit Simulator" that allows users to visualize and interact with quantum circuits. It demonstrates fundamental quantum mechanics principles using a simple circuit that creates a superposition of two states and measures the result.

Features
- Quantum Circuit Simulation: Implements a basic quantum circuit.
- Interactive Dashboard: Users can manipulate quantum gates and observe changes.
- Visualization Tools: Plots quantum state evolution.
- Minimalistic and Efficient Code: Designed for easy understanding.

Installation
Requirements
Python 3
Jupyter Notebook
Qiskit (for quantum computing)
Matplotlib (for visualization)
Streamlit (for interactive UI)

### Setup
```sh
pip install qiskit matplotlib streamlit
```

## Usage
1. Clone this repository:
   ```sh
   git clone https://github.com/your-repo/Quantum-Circuit-Simulator.git
   cd Quantum-Circuit-Simulator
   ```
2. Open the Google Colab Notebook:
   ```sh
  https://colab.research.google.com/drive/197roa6CBa1UPk-zA6SuyNlkj9EY8Gb3Q?authuser=0#scrollTo=Oqavgxqlexn0
   ```
Code Structure
- `Quantum_Circuit_Simulator.ipynb` - Jupyter Notebook implementing the quantum simulation.
- `dashboard.py` - Interactive dashboard for quantum circuit visualization.
- `requirements.txt` - Dependencies for easy setup.

## Example Quantum Circuit
The notebook constructs a quantum circuit with:
1. **Hadamard Gate (H)**: Creates superposition.
2. **Measurement**: Reads quantum state.

```python
from qiskit import QuantumCircuit, Aer, execute
import matplotlib.pyplot as plt

qc = QuantumCircuit(1, 1)
qc.h(0)  # Apply Hadamard gate
qc.measure(0, 0)
qc.draw()
```
Output Visualization
The circuit measurement results are plotted using Matplotlib, showing the probability of each outcome.

Contributions
Contributions are welcome! Feel free to open issues and submit pull requests.

License
This project is licensed under the MIT License.

