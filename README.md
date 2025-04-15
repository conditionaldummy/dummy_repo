# Conditional Distribution Compression via the Kernel Conditional Mean Embedding

This repository provides a python package to construct compressed sets targeting the JMMD and the AMCMD. The code is based on that found [here]([https://github.com/trevorcampbell/bayesian-coresets](https://github.com/gchq/coreax)).
It contains code to run the experiments in [Conditional Distribution Compression via the Kernel Conditional Mean Embedding](https://arxiv.org/abs/2504.10139).

### Installation and Dependencies

To install with pip, download the repository and run `pip install .` in the repository's root folder.

### Instructions 

In order to run the experiments, place `run_experiments.sh` in the same folder as the various experiment python scripts, and from a terminal in the relevant folder, run `chmod +x /run_experiments.sh` followed by `./run_experiments.sh`.
