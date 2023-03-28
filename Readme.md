# "Machine learning" course Final Project
## Team: ClosedAI_ML_Project

Hello! We are ML team who is predicting whether the bank clients have higher education or not using the embeddings, built through variety of models on datasets of transactions and clickstreams.

### Team members:

- Denis Grankin
- Ekaterina Anreichuk
- Ivan Apanasevich
- Mikhail Konenkov
- Irena Gureeva
## Topic: Contrastive Learning for Event Sequences with Self-Supervision on multiple domains
This repository contains Python code for conducting experiments to compare CoLES with other methods of embeddings creation baseline methods, such as Random Encoder and Agg baseline on different types of sequential data: transactions and clickstream. Also several experiments to define best parameters for CoLES was conducted.
![alt text](pics/General_Coles_framework.png)
CoLES is a self-supervised method for embeddings, which is based on contrastive learning. This method aims to learn a representation such that it brings closer semantically similar pairs closer to each other in embeddings space, while brings dissimilar objects further apart.
## Related documents
[Repository](https://github.com/dllllb/pytorch-lifestream) of the `pytorch-lifestream` library that was used during this project. <br>
[CoLES](https://arxiv.org/abs/2002.08232) paper, which introduce CoLES method and presents experiments with it. In the framework of our project we were to replicate this paper.
##
