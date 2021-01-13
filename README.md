# <h1 align=center>Convolutional Neural Networks</h1>

<div style="text-align: center;">

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1CiR8Q7q09nBIUmn5WHml9hW7y1Te5giH?usp=sharing)

</div>

In the deep learning and computer vision world, CNNs are getting more and more popular due to their high-performance
results. Thanks to this, it became very straight-forward to create and build convolutional models using different
frameworks such as Keras or TensorFlow. This implementation has been done with Keras.

The model has 3 convolutional layers with dropouts, flatten output of convolutions, and final dense output layer.
The dataset used for this study is CINIC-10, an augmented extension of CIFAR-10 which contains 270,000 images.

See more about the dataset: https://www.kaggle.com/mengcius/cinic10

Additionally, this notebook has VGG-16 and ResNet-50 models with the last 4 layers trainable. As these models require
the input shape to be 224x224x3, the images have to be resized before feeding to the models.