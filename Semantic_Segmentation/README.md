# Semantic Segmentation

Semantic segmentation task assign a class label to each pixel in an image resulting is an image that is segmented by each object.
In this project, the Segnet network have been implemented which was introduced in the paper entitled "SegNet: A Deep Convolutional Encoder-Decoder Architecture for Image Segmentation" by Vijay Badrinarayanan et al. 

## Dataset
We use Camvid dataset for trainig and inference: <br/>
https://s3.amazonaws.com/fast-ai-imagelocal/camvid.tgz <br/>
http://mi.eng.cam.ac.uk/research/projects/VideoRec/CamVid/data/LabeledApproved_full.zip <br/>

## Preprocessing:
multiple preprocess method are used 
- resizing images
- creating codecs (labels) for each pixels
- one hot encoding for label of pixels

## Training
after deviding data to 3 sets of train, validation and test, the SegNet Network is trained with proposed data for 2 cases (network with batch normalization and network without bach normalization. 


## Results
results for segmentation of test images for the network without batch normalization is shown below
![output of network](output.png "output of network for segmentation")
