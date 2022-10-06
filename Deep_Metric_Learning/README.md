# Deep Metric Learning
The goal of Deep Metric Learning is to learn an embedding space where, semantically similar objects are loacated nearby and disimilar objects far from another.
This project is implemented in pytorch.<br/>


## Dataset
We use LFW dataset for training and inference.


## Training
This project is about face recognition task and we use siamese network for training.
 we compare resualt with four different methods:
 
  - Circle loss with duplicated images
  - Circle loss without duplicated images
  - Triplet loss with duplicated images
  - Triplet loss without duplicated images
  

## Resualts

| Loss function                          | Time(minutes) |
| -------------                          | ------------  |
|Triplet loss with duplicated images     |      23       |
|Triplet loss without duplicated images  |      3.5      |
|Circle loss with duplicated images      |      53       |
|Circle loss without duplicated images   |      3.7      |
