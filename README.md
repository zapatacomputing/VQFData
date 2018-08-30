# Variational Quantum Factoring (VQF) Algorithm

Eric R. Anschuetz, Jonathan P. Olson, Alán Aspuru-Guzik, and Yudong Cao

The purpose of this repository is primarily to share raw data coming from our numerical experiments, to make it as easy as possible for anyone who would like to replicate our results to examine and compare with what we obtained. A copy of the paper is attached as `variational-quantum-factoring.pdf`. Also contained is the disclosure of invention as `disclosure-hybrid-algorithm.pdf`.

Within each data folder and given a depth, noise rate, and iteration number,
* `ansatze.npy` gives the VQF ansatz parameters,
* `computational_basis_state_fidelities.npy` gives the squared overlap of the VQF ansatz with each computational basis state,
* `ground_state_fidelities.npy` gives the squared overlap of the VQF ansatz with the factoring Hamiltonian ground state manifold,
* `num_opt_evalses.npy` gives the number of function evaluations the BFGS optimization uses, and finally
* `solution_state_fidelities.npy` gives the squared overlap of the VQF ansatz with the factoring Hamiltonian solution state manifold.

