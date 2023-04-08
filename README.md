# ITNPAI1 - Car and Tree Classification
# ![cover](https://user-images.githubusercontent.com/126859290/230741655-ff3e9258-5834-4e01-aa76-f2a44f1c05c9.jpg)

## Project Details

The aim project is focused on classifying cars and trees using deep learning. The Project is using a convolutional neural network (CNN) model to classify the images. This type of model is well-suited for image classification tasks due to its ability to learn spatial hierarchies of features.

## Model Architecture

The Project having a model architecture consisting of several convolutional and max pooling layers, followed by a dropout layer to reduce overfitting and two dense layers for classification. The model has a total of 8,417,505 trainable parameters. Two different models trained on the data for each city using the Adam optimizer and binary crossentropy loss function.

## Dataset & Data Processing Details

The dataset contain 400 images of cars and 400 images of trees collected equally from each city Glasgow (A) and Stirling (B). In cities data we have full images and cropped images, the cropped images is cropped from full images in order to train a machine learning model. and the trees data composed of some images from both cities and some images are collected from an open source website which is mentioned below in referenece section as we knew that their is not enough amount of trees exits in cities. All the images first through by OpenCv library and then reshape and rescale all images, the images belong to to cars folder assign label 0 ad the images belong from trees folder assign as label 1.

## Results

The results show that the models performs well on both the training and testing data. For city A, the training accuracy is 92.5% and the testing accuracy is 90.05%,  with an F1 score of 90.99%. For city B, the training accuracy is 89.50% and the testing accuracy is 86.05%, with an F1 score of 88.0%. When tested on the dataset from the other city, the model for city A achieves an accuracy of 88.05% and an F1 score of 88.99% on the city B dataset, while the model for city B achieves an accuracy of 86.0% and an F1 score of 87.61% on the city A
dataset.

## Reference

Trees dataset collection: [here](https://images.cv/download/tree/664/CALL_FROM_SEARCH/%22tree%22)

Algorithm Understanding: [here](https://www.analyticsvidhya.com/blog/2020/10/create-image-classification-model-python-keras/)
