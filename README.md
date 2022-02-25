# Face Mask Detection
## Table of Contents
- [Overview](#Overview)
- [Libraries](#Libraries)
- [Data](#Data)
- [Model](#Model)
- [Metrics](#Metrics)
## Overview
It's a CNN model takes a face image and tells you whether there's a mask or not.
## Libraries
* Tensorflow
* Pandas
* Numpy
* Matplotlib
* Seaborn
* Sklearn
## Data
Data was collected from Kaggle as two folders directories:
* with_mask folder contains 3725 images.
* without_mask folder contains 3828 images.
> Follow this link to reach the [Data](https://www.kaggle.com/omkargurav/face-mask-dataset)
## Model
It's divided to:
* Two convolution layers.
* Two pooling layers.
* one flatten layer.
* three dense layers.
> In the output dense layer k = 2, to classify the results whether with_mask or without_mask as sparse_categorical_crossentropy
## Metrics
* Accuracy.
* Precision, Recall and f1_score.
