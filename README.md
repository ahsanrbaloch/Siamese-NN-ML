# Siamese-NN-ML
This repository contains a jupyter notebook Siamese.ipynb for the training and testing og Siamese Neural Network on Stanford Dogs Dataset
The code manages a dataset of dog images from the [Stanford Dogs Dataset](http://vision.stanford.edu/aditya86/ImageNetDogs/) It involves several key components:

1.  Data Preparation and Organization: The dataset is organized into folders based on different dog breeds. Images are randomly sampled from each breed folder to create pairs of similar and dissimilar images for training a Siamese network.

2.  Siamese Network Training: A Siamese neural network is implemented using PyTorch. The network architecture consists of convolutional layers followed by fully connected layers. The network is trained using pairs of images to learn a similarity metric.

3.  Evaluation Metrics: After training, the Siamese network is evaluated using various metrics such as cosine similarity and Pearson correlation coefficient to measure the similarity between pairs of images.

4.  File Management Functions: Functions are provided to copy, move, and rename files, facilitating dataset management and organization.

5.  Dataset Organization: Folder paths are defined, and necessary folders are created to store images based on their similarity.
