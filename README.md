# Traffic_Light_Classifier

## Introduction
 Traffic Light Classifier use computer vision techniques to build a classifier for images of traffic lights! The given dataset of traffic light images in which one of three lights is illuminated: red, yellow, or green.

<div style="text-align:center">
<img src="https://github.com/jackyhuynh/Traffic_Light_Classifier/blob/main/images/all-lights.png" width="400" height="200"></div>

## Classification Steps
In the provided notebook, we'll pre-process these images, extract features that will help distinguish the different types of images, and use those features to classify the traffic light images into three categories: red, yellow, or green. The tasks will be broken down into a few sections:

1. Loading and visualizing the data. The first step in any classification task is to be familiar with the data; we'll need to load in the images of traffic lights and visualize them!

2. Pre-processing. The input images and output labels need to be standardized; that is, all the input should be of the same type of data and of the same size, and the output should be a numerical label. This way, we can analyze all the input images using the same procedures, and we know what output to expect when we eventually classify a new image.

![img](https://github.com/jackyhuynh/Traffic_Light_Classifier/blob/main/images/processing-steps.png)
<div style="text-align:center">Pre-processed, standardized images</div>

3. Feature extraction. I'll extract some features from each image that will be used to distinguish and classify these images. Features should be 1D vectors or even single values that provide some information about an image that can help classify it as a red, yellow, or green traffic light.

![Img](https://github.com/jackyhuynh/Traffic_Light_Classifier/blob/main/images/feature-ext-steps.png)
<div style="text-align:center">An example of feature extraction steps</div>

4. Classification and visualizing error. Finally, we'll write one function that uses our features to classify any traffic light image. This function will take in an image and output a label. we'll also be given code to classify a test set of data, compare our predicted label with the true label, and determine the accuracy of the classification model.

5. Evaluate the model. To pass this project, the classifier must be >90% accurate and never classify any red lights as green; it's likely that we'll need to improve the accuracy of the classifier by changing existing features or adding new features. Try to get as close to 100% accuracy as possible!

Next, read through the instructions and get ready to build a classifier!