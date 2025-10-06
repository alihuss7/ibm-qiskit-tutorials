# IBM Qiskit Tutorials

A collection of Jupyter notebooks exploring quantum computing concepts using IBM Qiskit.

## Episodes

- **Episode 2**: Installation - Setting up Qiskit and the development environment
- **Episode 3**: Hello World - Introduction to quantum circuits and basic operations
- **Episode 4**: Primitives - Working with Qiskit primitives for quantum computations
- **Episode 5**: Dynamic Circuits - Exploring dynamic quantum circuits and conditional operations
- **Episode 6**: Contributing - Guidelines for contributing to quantum computing projects

## Setup Instructions

### 1. Create Python Environment

```bash
conda create -n qiskit-env-py310 python=3.10
conda activate qiskit-env-py310
```

### 2. Install Required Packages

```bash
pip install qiskit qiskit-ibm-runtime qiskit_aer 'qiskit[visualization]' 'qiskit[machine-learning]'
```

### 3. Configure IBM Quantum Credentials

1. Copy the template configuration file:

   ```bash
   cp config_template.py config.py
   ```

2. Get your IBM Quantum token:

   - Visit [IBM Quantum Platform](https://quantum.ibm.com/)
   - Sign up or log in to your account
   - Navigate to your account settings
   - Copy your API token

3. Edit `config.py` and replace `YOUR_IBM_QUANTUM_TOKEN_HERE` with your actual token

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Then open any of the episode notebooks to start learning!

## Security Note

⚠️ **Important**: The `config.py` file contains your sensitive IBM Quantum credentials and is excluded from version control via `.gitignore`. Never commit this file to GitHub or share it publicly.

## Requirements

- Python 3.8+
- Qiskit
- Jupyter Notebook
- IBM Quantum account (free at [quantum.ibm.com](https://quantum.ibm.com/))

## License

This project is for educational purposes.
