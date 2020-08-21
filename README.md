# Animal-Classification
This repository contains the convolutional neural net built to classify animals between dogs and cats

This notebook is a form of submission for the Kaggle Competition: Dogs vs. Cats: https://www.kaggle.com/c/dogs-vs-cats

The data is available at https://www.kaggle.com/c/dogs-vs-cats/data which contain <b>25,000 cummulative images</b> for dogs and cats.

This network was able to achieve 80% accuracy with a subset of 2,000 total images (in an approximate 50:50 ratio). 
Data augmentation was achieved with the help of <b>Keras preprocessing ImageGenerator</b> to maximise the output of the data at each epoch. Tensorflow is the backend used for this project.
