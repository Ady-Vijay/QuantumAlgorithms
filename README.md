# Quantum Algorithms

Classical simulations of quantum algorithms, developed as part of my **honors thesis** at Texas A&M University (Advisor: Dr. Shenglong Xu, 2021–2024).

---

## Thesis: Quantum Algorithm for the Number Partition Problem

The central contribution of this work is a novel quantum algorithm for the **Number Partition Problem** — an NP-Hard combinatorial optimization problem — using two quantum mechanical principles:

1. **Measurement-induced state collapse** — projective measurement forces the system into a basis state, enabling probabilistic search
2. **Randomized Hamiltonian evolution** — evolving under a time-dependent Hamiltonian with randomized evolution times spreads amplitude across the search space

The algorithm leverages quantum superposition to explore the partition space and uses interference to amplify the probability of finding balanced partitions.

### Classical simulations implemented

| Notebook | Description |
|----------|-------------|
| Grover's Search | Full simulation of Grover's algorithm — oracle construction, diffusion operator, amplitude amplification over N iterations |
| Hamiltonian Evolution | Time evolution under a custom Hamiltonian; randomized evolution time sampling |
| Number Partition Solver | The full thesis algorithm applied to NP-Hard partitioning instances |
| 2D Ising Model | Statistical mechanics simulation — Monte Carlo approach to modeling ferromagnetic phase transitions |

All simulations are implemented in **NumPy** — no quantum computing framework dependencies. The goal was to understand the algorithms from first principles, not to use a black-box SDK.

---

## Running the notebooks

```bash
git clone https://github.com/Ady-Vijay/QuantumAlgorithms
cd QuantumAlgorithms
pip install numpy jupyter matplotlib
jupyter notebook
```
