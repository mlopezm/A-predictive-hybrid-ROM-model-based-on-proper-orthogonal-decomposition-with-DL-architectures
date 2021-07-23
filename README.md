# A-predictive-hybrid-ROM-model-based-on-proper-orthogonal-decomposition-with-DL-architectures
Code of the paper: "A predictive hybrid reduced order model based on proper orthogonal decomposition combined with deep learning architectures"

This repository contains the code and dataset files for the paper: "A predictive hybrid reduced order model based on proper orthogonal decomposition combined with deep learning architectures", R. Abadia-Heredia, M. Lopez-Martin, B. Carro, J.I. Arribas, J.M. Perez and S. Le Clainche.

All code files are available in this (github) repository. The description of the different files is as follows:

- Cilin3D_20 v2.0.ipynb: It provides an implementation of the CNN1D and LSTM models for the cilind3d_Mat dataset. It includes the initial SVD transformation. 

The code is prepared to make predicitions with k snapshots used as predictors to predict p time-ahead snaphots. In particular, in the code are used: p = 6 and k = 10. The results included in the paper present only the first time-ahead prediction (of the p available). 

The code and the dataset provided in this repository represent a representative example of the models and datasets used in the paper. The original raw dataset used as an example is provided in the following repository: .............

The code can be executed in the cloud using Google Colaboratory https://colab.research.google.com/notebooks/intro.ipynb
