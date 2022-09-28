# Crowd counting
Crowd counting or crowd estimating is a technique used to count or estimate the number of people in a crowd [(Wikipedia)](https://en.wikipedia.org/wiki/Crowd_counting).

Nowadays with help of Deep Learning, we can do this task with neural networks. In this project the model is impelented of paper entitled "Towards Perspective-Free Object Counting with Deep Learning" by Daniel O˜noro-Rubio et al.


## Preprocess:
In the fisrt step converting images to gray-scale, resizing and rescaling the coordinates of each point in the image.
Then gussain filter  is being applied in each coordination.
after these steps the data is ready for training.
Due to the small amount of data, augmentation methods have also been used to reach better results.

## Training
- ADAM Optimizer is used for training network and for loss functions, euclidean loss is used with power of 2.
- We initialize epochs to 30.

## Results
A sample of result:

<img src="img/pic-2.png" data-canonical-src="img/pic-2.png" width="400" />


