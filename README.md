# Data LABS BF-DCQO Benchmark

This repository contains the data of the low autocorrelation binary sequences (LABS) benchmark using the quantum optimization benchmarking framework [1].
We studied the scaling of BF-DCQO [2,3] by means of statevector simulations up to 30 qubits. Then, we tackled experimentally the 20-qubit problem . 
The LABS problem maps to an Ising Hamiltonian containing two- and four-body terms, and whose ground state encodes the optimal solutions. We used Qiskit [4] to build, transpile and send tasks to hardware. 
## Repository structure

The repository contains the following files

* `results_ibm` : A folder containing the raw data of both simulations and experiments.
* `notebooks` : Read the raw data and plot it.


## References

[1] Will be updated when the paper is public.

[2] Gomez Cadavid, Alejandro *et al.*, Bias-field digitized counterdiabatic quantum optimization. arXiv:2405.13898, arXiv, 22 May 2024. arXiv.org, arxiv.org/abs/2405.13898.

[3] Romero, Sebastian V. *et al.*, Bias-Field Digitized Counterdiabatic Quantum Algorithm for Higher-Order Binary Optimization. arXiv:2409.04477, arXiv, 05 Sep 2024. arXiv.orh arxiv.org/abs/2409.04477.

[4] Javadi-Abhari, Ali, *et al*. Quantum Computing with Qiskit. arXiv:2405.08810, arXiv, 15 May 2024. arXiv.org, arxiv.org/abs/2405.08810.

