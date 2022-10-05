# Relation Extraction

Relation Extraction is the task of predicting emantic relation between entities in a sentence. 
This Project is an implementation of paper entilted "Relation Classification via Recurrent Neural Network" by Dongxu Zhang et al.
This project is implemened using Pytorch.

## Preprocessin
Several preprocessing methods are used:
- Creating Dictionary for Tokens
- Encoding labels

## Training
We compare the resualts with three different methods:
- Using Bi-LSTM Network and pretrained Gloves for embedding
- Using Bi-LSTM Network and random initialization for embedding
- Using Bi-LSTM Network and random initialization for embedding with addition of Max-pooling and Average-pooling layers

