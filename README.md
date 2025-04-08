# Repository for Time-Rescaled Feedback Quantum Algorithms

This repository contains two notebooks implementing **Feedback Quantum Algorithms** with **Time-Rescaling**, applied to optimization problems and physical models.

## Contents

- **TR_FQA_ANNNI_Model.ipynb**  
  Implements the **Time-Rescaled Feedback Quantum Algorithm (TR-FQA)** for the **ANNNI model** (Axial Next-Nearest Neighbor Ising Model).  
  The notebook includes the Hamiltonian construction and the application of TR-FQA to approximate the ground state.

- **TR_FALQON_MaxCut.ipynb**  
  Implements the **Time-Rescaled Feedback-based Quantum Optimization Algorithm (TR-FALQON)** for the **MaxCut problem**.  
  The notebook defines the MaxCut Hamiltonian and applies TR-FALQON to search for approximate solutions.

## Requirements

- Python 3.8+
- Libraries:
  - `torch`
  - `numpy`
  - `matplotlib`
  - `networkx`


## Usage

Open the notebooks in Google Colab and run the cells sequentially.
Alternatively, download them and run locally with Jupyter Notebook or JupyterLab.

## Structure

Each notebook contains:
- Function definitions.
- Initial parameter settings.
- Hamiltonian construction.
- Algorithm application.
- Analysis and visualization of results.
