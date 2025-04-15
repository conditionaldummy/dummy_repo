# Conditional Distribution Compression via the Kernel Conditional Mean Embedding

This repository provides a python package to construct compressed sets targeting the JMMD and the AMCMD. The code is based on that found [here](https://github.com/gchq/coreax).

# Installation
To install with pip, download the repository and run `pip install .` in the repository's root folder. It is recommended to do so in a fresh virtual environment to ensure correct package versions are installed.

Coreax defaults to installing CPU-only JAX, if one has access to a GPU, after installation of Coreax run `pip install -U "jax[cuda12]"`.

Coreax does not come packaged with pandas, in order to run the real data experiments, pandas must be installed.

# Instructions
In order to run the experiments, first download the supplemental material and place `run_experiments.sh` in the same folder as the various experiment python scripts. Then, from a terminal in the relevant folder, run `chmod +x /run_experiments.sh` followed by `./run_experiments.sh`.
