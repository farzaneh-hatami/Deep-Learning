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

## Architecture

the following architecture is Segnet:
<img src="imgs/architecture.png" data-canonical-src="img/architecture.png" width="400" /><br/>
Segnet has 13 Encoder/Decoder layers.In this project we implemeted SegnetBase architecture which is similar to segent architecture unless it has 4 Encode/Decoder.

## Training

Two different method have been implemented:
- Network with batch Normalization 
- Network without batch Normalization

## Resualts

A sample of resualts:

resualts without batch normalization: <br/>
<img src="imgs/resualts_without_bn.PNG" data-canonical-src="img/resualts_without_bn.PNG" width="400" />

resualts with batch normalization: <br/>
<img src="imgs/resualts_with_bn.PNG" data-canonical-src="img/resualts_with_bn.PNG" width="400" />
