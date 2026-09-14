# CrossAttn-VAE-GAN: Cross-Modal Learning for Generalizable and Interpretable Drug–Target Interaction Prediction

This repository contains the implementation of CrossAttn-VAE-GAN, a multimodal deep learning framework for Drug–Target Interaction (DTI) prediction.

### Overview

The proposed framework integrates:

* ChemBERTa for drug representation learning from SMILES sequences.
* ESM-2 and GraphBERT for protein representation learning.
* Cross-Attention mechanism for multimodal feature fusion.
* Variational Autoencoder (VAE) for latent representation learning.
* Generative Adversarial Network (GAN) for improving latent feature quality.
* Cosine-based classifier for binary DTI prediction.

### Datasets

Experiments were conducted on:

* BIOSNAP
* DAVIS
* BindingDB

### Repository Structure

* biosnap_py.py : BIOSNAP experiment.
* davis_py.py : DAVIS experiment.
* bindingdb_py.py : BindingDB experiment.

### Requirements

Python 3.10+

Main libraries:

* PyTorch
* Transformers
* Scikit-learn
* NumPy
* Pandas

### Results

The proposed model achieved strong performance across multiple benchmarks and demonstrated improved generalization under unseen drug and unseen protein settings.

### Author

Sara Aljuaid and Ohood Althobaiti (IEEE member)
### Citation

If you use this repository, please cite the corresponding thesis or publication.
