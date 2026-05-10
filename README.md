# Linear Algebra for Quantum Computing

> **The mathematics behind quantum computing — built from first principles.**

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://www.python.org/)
[![NumPy](https://img.shields.io/badge/NumPy-1.21%2B-013243?logo=numpy)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.4%2B-11557c)](https://matplotlib.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## Why This Repository Exists

Most quantum computing tutorials start with circuits and gates — and immediately hit a wall when eigenvalues appear. This repository starts one step earlier, building the linear algebra intuition that makes quantum mechanics readable rather than mysterious.

If you have ever stared at the equation $H|\psi\rangle = E|\psi\rangle$ and wondered what it actually means, this is your starting point.

---

## Contents

| Notebook | Topics Covered | Level |
|---|---|---|
| [`eigenvalues-eigenvectors.ipynb`](eigenvalues-eigenvectors.ipynb) | Eigenvalues, eigenvectors, geometric visualisation, connection to quantum Hamiltonians | Beginner–Intermediate |

More notebooks coming — spanning matrix decompositions, tensor products, and the Bloch sphere.

---

## What You Will Learn

**Eigenvalues and Eigenvectors** — the mathematical foundation of every quantum measurement:

- What eigenvectors mean *geometrically* (not just algebraically)
- How a matrix transformation stretches space — and which directions stay fixed
- How to compute eigendecomposition numerically with NumPy
- How to visualise eigenvectors on a transformed coordinate space
- Why this maps directly to quantum observables, measurement outcomes, and the VQE algorithm

---

## The Quantum Connection

| Linear Algebra | Quantum Computing |
|---|---|
| Matrix $A$ | Hamiltonian operator $H$ |
| Eigenvector $\mathbf{v}$ | Quantum state $\|\psi\rangle$ |
| Eigenvalue $\lambda$ | Energy measurement outcome $E$ |
| Smallest eigenvalue | Ground state energy |
| Finding smallest eigenvalue | What VQE solves |

Understanding this table is the difference between *running* a quantum algorithm and *understanding* one.

---

## Quick Start

### Requirements

```bash
pip install numpy matplotlib jupyter
```

### Run the Notebook

```bash
git clone https://github.com/fatahjamro/linear-algebra-for-quantum-computing.git
cd linear-algebra-for-quantum-computing
jupyter notebook eigenvalues-eigenvectors.ipynb
```

Or open directly in [VS Code](https://code.visualstudio.com/) or [Marimo](https://marimo.io/).

---

## About the Author

**Abdul Fatah** — PhD Researcher in Quantum Computing and Computer Science, Atlantic Technological University (ATU) Galway, Ireland.

Specialising in quantum error correction, quantum cryptography, and quantum combinatorial structures. Research recognised by ETH Zurich, Oxford University (NQCC), and published in IEEE QCNC.

- **GitHub:** [github.com/fatahjamro](https://github.com/fatahjamro)
- **LinkedIn:** [linkedin.com/in/fatahjamro](https://linkedin.com/in/fatahjamro)
- **QuantumBeads:** [quantumbeads.com](https://quantumbeads.com)

---

## Part of the QuantumBeads Learning Initiative

This repository is part of [QuantumBeads](https://quantumbeads.com) — an open initiative for accessible, rigorous quantum computing education.

If this was useful, please consider **starring the repository ⭐** — it helps others find it.

---

## Licence

MIT — free to use, share, and build upon with attribution.
