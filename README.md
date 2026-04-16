# IBM Qiskit Tutorials

Hands-on Jupyter notebooks to learn quantum computing with Qiskit and IBM Quantum.

## Repo Description

Practical Qiskit tutorials that cover setup, circuits, primitives, dynamic circuits, and contribution basics.

## Topic Tags

`qiskit`, `ibm-quantum`, `quantum-computing`, `python`, `jupyter-notebook`, `tutorials`, `dynamic-circuits`

## Tutorials

- Episode 2: Installation
- Episode 3: Hello World
- Episode 4: Primitives
- Episode 5: Dynamic Circuits
- Episode 6: Contributing

## Quick Start

```bash
conda create -n qiskit-env-py310 python=3.10
conda activate qiskit-env-py310
pip install qiskit qiskit-ibm-runtime qiskit_aer 'qiskit[visualization]' 'qiskit[machine-learning]'
cp config_template.py config.py
jupyter notebook
```

## IBM Quantum Token

1. Sign in at [quantum.ibm.com](https://quantum.ibm.com/).
2. Copy your API token from account settings.
3. Put the token in `config.py`.

## Security

`config.py` contains private credentials and is ignored by git. Do not commit it.

## Requirements

- Python 3.8+
- Qiskit
- Jupyter Notebook
- IBM Quantum account

## Usage

Built for learning and practice.
