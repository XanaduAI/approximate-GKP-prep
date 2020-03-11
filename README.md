# Approximate GKP states

### Understanding how approximate GKP states behave under basic gate applications, and how the states can be prepared using Gaussian Boson Sampling-type devices.


This repository contains the source code used to produce the results presented in *"Progress towards practical qubit computation using approximate Gottesman-Kitaev-Preskill codes"*.

## Contents

For more details see individual code files.

* `Formalism.ipynb`: a Jupyter notebook to calculate 1) how GKP states are modified by single and two qubit gates, and 2) how to get a class of optimal stellar representations (Fock superposition followed by squeezing) of normalizable GKP states.

* `StatePrepCircuits.ipynb`: a Jupyter notebook to optimize optical circuits with squeezers, phase shifters, beamsplitters, and PNR detectors for the preparation of GKP states and general non-Gaussian states.

* `paper_data`: GBS circuit parameters used to produce the quantities in Table II of the paper.

* `target_data`: Fock superposition and squeezing parameters of approximate GKP states to be used to train GBS state preparation device parameters.

* `test_data`: a file where basic test runs from `StatePrepCircuits.ipynb` can be stored.

## Authors

Ilan Tzitrin, J. Eli Bourassa, Nicolas C. Menicucci, and Krishna Kumar Sabapathy

If you are doing any research using this source code, the Walrus and Strawberry Fields, please cite the following papers:

> Ilan Tzitrin, J. Eli Bourassa, Nicolas C. Menicucci, and Krishna Kumar Sabapathy. Towards practical qubit computation using approximate error-correcting grid state. https://arxiv.org/abs/1910.03673

> Brajesh Gupt, Josh Izaac and Nicolás Quesada. The Walrus: a library for the calculation of hafnians, Hermite polynomials and Gaussian boson sampling. Journal of Open Source Software, 4(44), 1705 (2019)

> Nathan Killoran, Josh Izaac, Nicolás Quesada, Ville Bergholm, Matthew Amy, and Christian Weedbrook. Strawberry Fields: A Software Platform for Photonic Quantum Computing. arXiv, 2018. [Quantum, 3, 129](https://quantum-journal.org/papers/q-2019-03-11-129/) (2019).

## License

This source code is free and open source, released under the Apache License, Version 2.0.
