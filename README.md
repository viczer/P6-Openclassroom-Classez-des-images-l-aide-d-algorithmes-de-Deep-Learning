# StanfordDogs

## Presentation

In this project, we use *Tensoflow ([Keras](https://keras.io/))* to implement and train *machine learning* algorithms to automatically detect *dog breeds* in pictures. 

We implement a *CNN (Convulotionnal Neural Network)* from scratch, and *fine-tune pre-trained models* thanks to *transfer learning*. We use *KerasTuner* for the hyperparameters search and *Tensorboard* to track the *results*.

We develop a wrapper for *Keras*, *KerasTuner* & *TensorHub* in order to :
* Automatically generate neural networks and their structure
* Train neural networks by applying hyperparameters search strategies
* Visualize the performances of the generated models

We develop a MVP with *Streamlit* for users to esaily classify theirs images to obtain a breed prediction using the drag & drop feature.

## Files Description

* ***P6_01_test_notebook.ipynb***: machine learning experiments & code for the wrapper
* ***P6_02_app_README.md***: README of the MVP and link to the github repo
* ***P6_03_app.zip***: source code of the MVP
* ***P6_04_presentation.pdf***: projects presentation slideshow (french)

## Data

The *training data* used in this notebook is the [*Stanford Dogs Dataset*](http://vision.stanford.edu/aditya86/ImageNetDogs/).
