# Leaf-Classification
Leaf classification using Convolutional Neural Network

## Project Description

the goal of this model is to create a method to classify leaves without relying on the presence of large datasets and manually identified features to for an algorithm, using a multi-tiered abstraction approach to deep learning algorithms. Because of the lack of a substanially large dataset the classification was left on a genus rather than a species level.

A deep learning CNN consists of three layers: a convolutional layer, a pooling layer and a fully connected (FC) layer. The convolutional layer is the first layer while the FC layer is the last.

From the convolutional layer to the FC layer, the complexity of the CNN increases. It is this increasing complexity that allows the CNN to successively identify larger portions and more complex features of an image until it finally identifies the object in its entirety.

In an attempt to optimize the model we manipulated some variables such as the number of layers, the number of filters, the size of filters, and the types of activations functions used in the hidden, or middle, layers of the model (e.g. ReLU). Since image data was limited, data augmentation was used to produce further image variation for model training/testing. 
