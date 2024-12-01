# Graph Autoencoder for Molecular Link Reconstruction and Prediction

This repository contains the implementation and experiments of Graph Autoencoder models to reconstruct and predict molecular interactions within the OmniPath network, a database representing molecular interactions.

## Overview
Understanding molecular relationships (e.g., between genes, proteins, and other molecules) is critical for tasks like:

- Identifying biological pathways
- Predicting disease associations
- Supporting drug discovery

The goal of this project is to:
- Develop and optimize Graph Autoencoder architectures to learn meaningful representations of the molecular interaction network.
- Reconstruct the OmniPath graph and evaluate the recovery of its network connections.
- Explore the potential of predicting new molecular interactions that might have important biological significance but are currently missing from the database.

This repository contains four Jupyter notebooks for streamlined experimentation. 

GAE.ipynb, VGAE.ipynb and GAT.ipynb models for a homogeneous graph. Hetero_GAT+VGAT.ipynb models for a heterogeneous graph. 

The detailed report can be found [here](https://drive.google.com/file/d/1CrJ_ILZj9T3Wzey4UbYcjc6yM1HP1CHx/view?usp=sharing). 
