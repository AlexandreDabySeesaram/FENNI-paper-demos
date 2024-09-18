# Welcome to [Škardová, Daby-Seesaram, Genet,  Submitted]. Finite Element Neural Network Interpolation: Interpretable Neural Networks for solving PDEs's demos!

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.13785982.svg)](https://doi.org/10.5281/zenodo.13785982)

These demos are based on the [NeuROM-py code](https://pypi.org/project/NeuROM-Py/) version 3.1.6 [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.13772741.svg)](https://doi.org/10.5281/zenodo.13772741) and allow reproducing most figures of our paper [Škardová, Daby-Seesaram, Genet, Submitted].

## Finite Element Neural Network Interpolation: Interpretable Neural Networks for solving PDEs 
In this paper, we present the Finite Element Neural Network Interpolation framework -- a structured neural network designed to perform interpolation using standard finite element shape functions.
Similarly to classical Physics-informed neural networks, the knowledge of the underlying physics is incorporated into the model through an appropriate definition of the loss function.

Due to the specific structure of the neural network, the number of trained parameters is significantly lower than in fully connected neural networks. The individual weights and biases have a clear interpretation. Thanks to this feature, the model can be used to solve PDEs of fixed mesh as well as r- and rh-adaptive ones without any change to the model architecture.
The interpretability also enables the strong imposition of Dirichlet boundary conditions, avoiding the challenges associated with including additional terms in the loss function. Furthermore, the model's specific architecture can be leveraged to implement transfer learning techniques.     

In this paper, we present the capabilities of the model in 1D and 2D test cases. The training is performed using several combinations of physics-informed loss functions, optimizers, and training strategies. The benefits and limitations of the tested variants are discussed. 
