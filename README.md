# MAT3036-Literature-Review

This repository contains all the code for the work produced in the MAT3036 Literature Review module at the University of Surrey, School of Mathematics and Physics.

The primary contribution of this repository is a PyTorch reimplementation of the Deep Convolutional Embedded Clustering (DCEC) model, developed as part of Chapter 6 of the accompanying report. The implementation was built from the original publication to reproduce and evaluate the proposed method.

- **Unsupervised Deep Embedding for Clustering Analysis:** https://arxiv.org/pdf/1511.06335
- **Deep Clustering with Convolutional Autoencoders:** https://xifengguo.github.io/papers/ICONIP17-DCEC.pdf

## Requirements

The project was developed using Python 3.12 and the following main libraries:

- [PyTorch](https://pytorch.org/)
- [NumPy](https://numpy.org/)
- [scikit-learn](https://scikit-learn.org/)
- [SciPy](https://scipy.org/)
- [Matplotlib](https://matplotlib.org/)

### Setup (Conda)

To install the required environment, run:

```bash
conda env create -f environment.yml
conda activate lit-review
