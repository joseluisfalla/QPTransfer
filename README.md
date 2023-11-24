# QAOA Parameter Transferability
Graph embedding techniques for parameter transferability in the quantum approximate optimization algorithm.

## Usage
This repository contains five main Jupyter notebook that takes a list of graphs (from the '/graphs' directory) to train a graph embedding model (five models in total; one Jupyter notebook for each) to predict good donor candidates for a target acceptor instance of MaxCut QAOA. The graphs in the '/graphs' directory have been pre-optimized for a QAOA depth of p = 3 and all sets of optimal gamma and beta parameters are stored in the '/graph_data' directory.

The five possible embedding techniques are: Graph2Vec, GL2Vec, SF, Wavelet Characteristic, and FEATHER.

These notebooks require the [KarateClub](https://karateclub.readthedocs.io/en/latest/notes/installation.html) and [QTensor](https://github.com/danlkv/QTensor) libraries.
