# (![cover](https://user-images.githubusercontent.com/126859290/230741565-3f1de0fa-e916-4ead-bff2-ab01930b06b0.jpg))

# ITNPAI1 - Car and Tree Classification

## Project Details

The aim project is focused on classifying cars and trees using deep learning. The Project is using a convolutional neural network (CNN) model to classify the images. This type of model is well-suited for image classification tasks due to its ability to learn spatial hierarchies of features.

## Dataset & Data Processing Details

The dataset contain 400 images of cars and 400 images of trees collected equally from each city Glasgow (A) and Stirling (B). In cities data we have full images and cropped images, the cropped images is cropped from full images in order to train a machine learning model. and the trees data composed of some images from both cities and some images are collected from an open source website which is mentioned below in referenece section as we knew that their is not enough amount of trees exits in cities. All the images first through by OpenCv library and then reshape and rescale all images, the images belong to to cars folder assign label 0 ad the images belong from trees folder assign as label 1.

## Reference

Trees dataset collection: [here](https://images.cv/download/tree/664/CALL_FROM_SEARCH/%22tree%22)

Algorithm Understanding: [here](https://www.analyticsvidhya.com/blog/2020/10/create-image-classification-model-python-keras/)
