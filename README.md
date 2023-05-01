# Cats_vs_Dogs_CNN

<p align="center">
  <img src="https://www.finder.com.au/niche-builder/5f7d3685592c8.jpg?fit=1200"/>
</p>

# Cat or Dog Classifier using Convolutional Neural Networks

This is a Deep Learning project that aims to classify images as containing either a cat or a dog. The project uses Convolutional Neural Networks (CNNs), a type of neural network commonly used for image classification tasks.

# Convolutional Neural Networks


<p align="center">
  <img src="https://d33wubrfki0l68.cloudfront.net/a7664cf19de33b2c71a482629f27a0d70f715b77/6949d/images/blog/a-comprehensive-guide-to-convolutional-neural-networks-the-eli5-way.jpg"/>
</p>

CNNs are a type of neural network that are designed to automatically learn features and patterns in image data. The architecture of a CNN consists of multiple layers, including convolutional layers, pooling layers, and fully connected layers.

The convolutional layers are the core of the network and apply filters to the input image to extract features. These features are then passed through pooling layers, which reduce the spatial size of the output and help to generalize the features learned by the network. Finally, the output is passed through fully connected layers, which use the extracted features to classify the image.

The main advantage of CNNs over other types of neural networks is their ability to effectively extract features from images. The convolutional layers in the network are able to learn filters that detect edges, corners, and other basic features in the image, while deeper layers can learn more complex features such as patterns and textures.

# Dataset
The dataset used for this project is "The Asirra dataset," which consists of over 25,000 images of dogs and cats annotated images of cats and dogs. The dataset was extracted from two different sources : Microsoft for the TensorFlow notebook and Kaggle for the PyTorch notebook.

# Notebooks
This project contains two Jupyter notebooks - one for TensorFlow and one for PyTorch. Both notebooks contain the same code and implement CNN architecture with some differences. The notebooks provide a step-by-step guide for training and evaluating the model, as well as for testing the model on new images.

# Dependencies
This project requires the following dependencies:
- You need a Kaggle account in order to retrieve the API key which give you the kaggle.json file. To retrive that in Kaggle, go on Setting => Create New Token or Expire Token then Create New Token.
- I recommend having a good GPU because of the runtime during training. Otherwise, you have to be very patient.

To use this project, simply download or clone the repository and open the Jupyter notebook for either TensorFlow or PyTorch. Follow the instructions in the notebook to train and test the model.

# Results

<p align="center">
  <img src="https://raw.githubusercontent.com/MetalGray/Cat_vs_Dogs_CNN/main/images_results.png" />
</p>

# Credits
This project was created by MetalGray and hlargitte. The dataset used for this project is "The Asirra dataset," which is available under the Microsoft but also in Kaggle. Here are the two URLs to retrieve the dataset :

- Microsoft : https://download.microsoft.com/download/3/E/1/3E1C3F21-ECDB-4869-8368-6DEBA77B919F/kagglecatsanddogs_5340.zip
- Kaggle : https://www.kaggle.com/competitions/dogs-vs-cats-redux-kernels-edition/overview/evaluation
