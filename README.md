# Traffic_Light_Classifier

## Introduction
 Traffic Light Classifier use computer vision techniques to build a classifier for images of traffic lights! The given dataset of traffic light images in which one of three lights is illuminated: red, yellow, or green.

<div style="text-align:center">
<img src="https://github.com/jackyhuynh/Traffic_Light_Classifier/blob/main/images/all-lights.png" width="800" height="300"></div>

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

## Helper functions and testing
Also included are some additional Python files: helpers.py and test_functions.py

These provide helper functions (that load in data) and test functions that will let you test the code as you go! 

## Technology
- Python 
- Jupyter Notebook
- Data Visualization
- Algorithms
- Open CV
- Machine Learning

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites
What things you need to install the software and how to install them
- Jupyter Notebook: If you want just test the code, simply go to google and search for jupiter notebook or another Python online IDE. The Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text. 
- Anacoda Navigator: Install Anaconda Navigator if you want to develop data sciences using python or R. Anaconda Navigator is a desktop graphical user interface included in Anaconda that allows you to launch applications and easily manage conda packages, environments and channels without the need to use command line commands. 
- OpenCV: OpenCV (Open Source Computer Vision Library) is an open source computer vision and machine learning software library. OpenCV was built to provide a common infrastructure for computer vision applications and to accelerate the use of machine perception in the commercial products. Being a BSD-licensed product, OpenCV makes it easy for businesses to utilize and modify the code. It has C++, Python, Java and MATLAB interfaces and supports Windows, Linux, Android and Mac OS. OpenCV leans mostly towards real-time vision applications and takes advantage of MMX and SSE instructions when available.

### Installing

A step by step series of examples that tell you how to get a development enviroment running

* [Install Anacoda Navigator](https://docs.anaconda.com/anaconda/navigator/install/#:~:text=Installing%20Navigator%20Navigator%20is%20automatically%20installed%20when%20you,install%20anaconda-navigator.%20To%20start%20Navigator,%20see%20Getting%20Started.) - If you haven't downloaded and installed Anacoda Navigator yet, here's how to get started.
* [Jupyter Notebook](https://jupyter.org/try) - Click here to go to the online free Jupiter Notebook.
* [OpenCV](https://opencv.org/)-To run this application we need Open CV installed in the local machine or using anacoda to install Open CV

## Running the tests

Explain how to run the automated tests for this system:
- There is no download IDE need, all you need is download all the src to your machine and run it.
- Or just open the jupiter notebook on Github
- Using Jupiter Notebook
- Navigate to the file .ipynb
- hit:
```
Ctrl + Enter
```

## Deployment

Can be deploy and ready to work with any sensor, selfdriving car or moving robotic prediction. Idea for localization and/or GPS application. 
Please refer to my notebook for a better understanding of implementation.

## Built With

* [Jupyter Notebook](https://jupyter.org/try) 

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Truc Huynh** - *Initial work* - [TrucDev](https://github.com/jackyhuynh)

## Format
my README.md format was retrieved from
* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Udacity.com for design outstanding programs for Students.

