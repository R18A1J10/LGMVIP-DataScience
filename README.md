# LGMVIP-DataScience

## Projects


### Task 01: Iris Flower Classification

There are three species of Iris Flower: Iris-Setosa, Iris-Versicolor, and Iris-Virginica. They differ from one another based on the change in measurement. Training a machine learning model to recognise and categorise species based on measurements.

1. Cleansing the data and naming it appropriately
2. Investigated the data by performing EDA, the proportion of data per species, and the relationships between the length and width of sepal and petal.
3. To create a machine learning model, the data is first divided into training and test datasets, and then logistic regression, DecisionTreeClassifier, and KNeighborsClassifier are done.
4. The accuracy for all three models was 100, indicating that the models are operating well.


### Task 02: Stock Price Prediction and Forecasting using stacked LSTM

1. LSTMs are commonly used to solve sequence prediction issues. They preserve crucial knowledge from the past, making it incredibly effective. It consists of three gates: an input gate, a forget gate, and an output gate.
2. Like with any other model, data is loaded initially, then train and test splits are conducted, followed by data pre-processing. Then there's the LSTM application, prediction, and conclusion.


### Task 03: Image to Pencil Sketch with Python

There are only four main steps to create a pencil sketch image in Python.
1. Changing a colour image to a grayscale image.
2. Invert the image's colours.
3. Soften the reversed picture.
4. To mix the blurred and grayscale images, use the dodge blend.

I used the image of my favourite football play Lionel Messi⚽ for this project.


### Task 04: Exploratory Data Analysis on Dataset-Terrorism 

1. Perform Exploratory Data Analysis on dataset ‘Global Terrorism’
2. As a security/defense analyst, try to find out the hot zone of terrorism.
3. What all security issues and insights you can derive by EDA?

The purpose of this notebook is to investigate terrorist events around the world. This notebook combines interactive plots and animations to make exploring easier and more informative.

Dataset Link: https://drive.google.com/file/d/1luTU7xBvI7QAGPbQMxEHcgKUi9d6UeP_/view


### Task 05: Prediction using Decision Tree Algorithm for Iris Dataset

1. A decision tree is a supervised ML model in which data is continually partitioned based on specific parameters before making a decision.
2. The necessary libraries are imported, followed by the data loading. The following goal is to extract the properties and targets. The train test split function has been imported and used.
3. The decision tree classifier is then built and evaluated against the training dataset. Finally, an accuracy score is calculated of the training and test data.


### Task 06: Develop A Neural Network That Can Read Handwriting

In this notebook, I have built a deep neural network on MNIST handwritten digit images to classify them. MNIST is called Hello World of Deep Learning and, its also my first image recognition task.

1. Importing MNIST Handwritten Digits Datasets from Keras library.
2. Visualizing a few random images from the training set.
3. As the pixel values range from 0 to 256, apart from 0 the range is 255. So we divide all the values by 255 which will convert it to range from 0 to 1.
4. The proposed model is based on MLP layers. Therefore, the input is expected to be a 1D tensor. So, x_train and x_test are reshaped to [60000, 28 28] and 
[10000, 28 28], respectively.
5. Build the CNN Model and fit our training data.
6. Then we evaluate the loss and accuracy of our model on the Test set.
7. Plotting random images from the test data set compared against the predicted results.
In this notebook, I have created a CNN model using MNIST handwritten digit images to classify them.

