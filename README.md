# IBM-Project-27678-1660062691
Fertilizers Recommendation System For Disease Prediction
## Project Objectives

Preprocess the images.

Applying the CNN algorithm to the dataset.

How deep neural networks detect the disease.

You will be able to know how to find the accuracy of the model.

You will be able to build web applications using the Flask framework.


## Team Members 

GURUMOORTHY J

MANOJ KUMAR N

BHARATH KUMAR K

PRAVEEN JOSEPH RATHNIAH 

## Project Flow

### A web Application is built  where: 

Farmers can interact with the portal build

Interacts with the user interface to upload images of diseased leaf

Our model built analyses the Disease and suggests the farmer with fertilizers are to be used 

### To accomplish the above task you must complete the below activities and tasks: 

Download the dataset.

Classify the dataset into train and test sets.

Add the neural network layers.

Load the trained images and fit the model. 

Test the model.

Save the model and its dependencies.

Build a Web application using a flask that integrates with the model built.


## Project Structure

The dataset folder contains two folders for the fruit and vegetable dataset which again contains a test and train folder, each of them have images of different diseases.

The Flask folder has all the files necessary to build the flask application. 

The static folder has the images, style sheets, and scripts that are needed in building the web page.

Templates folder has the HTML pages.

Uploads folder has the uploads made by the user

app.py is the python script for server-side computing.

.h5 files are the model files that are to be saved after model building.

Precautions excel files contain the precautions for all kinds of diseases.

Fruit-Training.ipynb, Vegetable-Training, and Plant-Disease-Testing.ipynb are the training and testing notebooks.

IBM folder contains IBM deployment files.


## Data Collection

### The first step is to download the dataset 

Create Train and Test folders with each folder having subfolders with leaf images of different plant diseases. You can collect datasets from different open sources like kaggle.com, data.gov, UCI machine learning repository, etc. The folder contains the provided in the project structure section has the link from where you can download datasets that can be used for training. Two datasets will be used, we will be creating two models one to detect vegetable leaf diseases like tomato, potato, and pepper plants and the second model would be for fruits diseases like corn, peach, and apple.


## Image Preprocessing

Now that we have all the data collected, let us use this data to train the model . before training the model you have to preprocess the images and then feed them on to the model for training. We make use of Keras ImageDataGenerator  class for image preprocessing.

Image Pre-processing includes the following main tasks:

Import ImageDataGenerator Library.

Configure ImageDataGenerator Class.

Applying ImageDataGenerator functionality to the trainset and test set.

### Note
The ImageDataGenerator accepts the original data, randomly transforms it, and returns only the new, transformed data.
Lets build model for fruit leaf disease detection
Open Jupyter notebook and create a new python file, name ii Fruit-Training.ipynb and save it in the project folder. To know more about the usage  of the Jupyter notebook watch the video given in the pre-requisites section

## Model Building For Fruit Disease Prediction

We are ready with the augmented and pre-processed image data, Lets begin our model building, this activity includes the following steps

Import the model building Libraries

Initializing the model

Adding CNN Layers

Adding Hidden Layer

Adding Output Layer

Configure the Learning Process

Training and testing the model

Saving the model
