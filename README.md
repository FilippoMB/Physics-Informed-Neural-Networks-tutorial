# Tutorial: Physical Informed Neural Networks

This tutorial gives a short introduction to Physical Informed Neural Networks (PINNs) and shows how to implement in Pytorch a PINN to model a growth function and a 1-dimensional wave.


💻 Notebook:
[![nbviewer](https://img.shields.io/badge/-View-blue?logo=jupyter&style=flat&labelColor=gray)](https://nbviewer.org/github/FilippoMB/Physics-Informed-Neural-Networks-tutorial/blob/main/tutorial.ipynb) or [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/FilippoMB/Physics-Informed-Neural-Networks-tutorial/blob/main/tutorial.ipynb)

---

This tutorial is based on the [original PINN paper](https://www.sciencedirect.com/science/article/pii/S0021999118307125), the official [software implementation](https://maziarraissi.github.io/PINNs/), and [this](https://towardsdatascience.com/solving-differential-equations-with-neural-networks-afdcf7b8bcc4) and [this](https://towardsdatascience.com/physics-and-artificial-intelligence-introduction-to-physics-informed-neural-networks-24548438f2d5) great posts, which introduce the PINNs from a machine learning and a physics perspective, respectively.