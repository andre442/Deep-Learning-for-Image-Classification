# Deep-Learning-for-Image-Classification
This repository contains a study of the use of CNN's for classification of manuscript images. All details are in the PDF file and the codes and dataset can be checked in the repository.

In this experiment, a database with images of the months of the year was used, totaling 12 classes. This database contains a total of 1979 samples, 1578 of which were set aside for training and 401 set aside for validation. All images are binary and are in .jpeg format. The first step of the experiment was carried out in the Jupyter Notebook environment.

To create the bases with 4734 training samples, the Data Augmentation technique was used and for each of the original samples, two extra samples were created, totaling a training base with triple the original size.

Keras and Sklearn frameworks were used to carry out the entire process of this first stage, including the normalization of images, generation of labels for the confusion matrix and the conversion of class vectors to binary matrices.
