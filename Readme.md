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
This repository contains Python code for conducting experiments to compare CoLES with other methods of embeddings creation, such as Random Encoder and Agg baseline on different types of sequential data: transactions and clickstream. Also several experiments to define best parameters for CoLES was conducted.
![alt text](pics/General_Coles_framework.png)
CoLES is a self-supervised method for embeddings, which is based on contrastive learning. This method aims to learn a representation such that it brings closer semantically similar pairs closer to each other in embeddings space, while brings dissimilar objects further apart.
## Prerequisites 
Most of the notebooks can be directly run in Google Collab.
For launching `notebooks/clickstreams.ipynb` PySpark is needed. The actions to configure PySpark can be found [here](https://www.datacamp.com/tutorial/installation-of-pyspark). <br>
Versions: `Spark version 3.3.2; Hadoop version 2.7` <br>
`findspark` module and `PySpark` module should also be installed via `!pip install findspark` and `!pip install PySpark` respectively.  
## Related documents
[Repository](https://github.com/dllllb/pytorch-lifestream) of the `pytorch-lifestream` library that was used during this project. <br>
[CoLES](https://arxiv.org/abs/2002.08232) paper, which introduce CoLES method and presents experiments with it. In the framework of our project we were to replicate this paper.
## Structure of the repository 
Main files, that represents out work are:
-  `./notebooks` directory contains jupyter notebooks with conducted experiments. More detailed description of contents of this notebooks are presented in `./notebooks/Readme.md`
- `./Docs` directory contains documents (Project presentation and Project Report), which presents our work in more detail.
## Datasets 
The data was taken from [Data Fusion 2022 competition](https://ods.ai/competitions/data-fusion2022-education/dataset). Main files are [transactions.zip](https://storage.yandexcloud.net/datasouls-ods/materials/0433a4ca/transactions.zip) (transactions dataset), [clickstream.zip](https://storage.yandexcloud.net/datasouls-ods/materials/0554f0cf/clickstream.zip) (clickstream dataset),[train_matching.zip](https://storage.yandexcloud.net/datasouls-ods/materials/acfacf11/train_matching.csv) (dataset of matched user IDs in clickstream dataset and transactions dataset), [train.csv](https://storage.yandexcloud.net/datasouls-ods/materials/e756bf99/train.csv) (dataset, containing the target for the downstream task)
## Results
