# Automated_MetalSurface_defects_detection
Objective:
Classifying the metal surface defects using Convoluted Neural Networks by image processing and building a deep learning model and also training and fine-tuning the model with a dataset of images of the metal surface.

Description:
A CNN consists of multiple layers, including convolutional, max-pooling, and dense layers. The network applies a set of learnable filters to the input image to extract features. These filters slide over the image in a process known as convolution, producing a feature map for each filter.
With CNN, this Classification Model also uses the following algorithms.
RMSprop optimizer, ImageDataGenerator, Max-Pooling layer, dropout layer

Sequential Methodology:
1.Image Processing: Load the training and validation images using the ImageDataGenerator class. 
2.The images are resized to 200x200 and normalized by dividing each pixel by 255 to make the pixel value between 0 to 1.
3.Define the Model: Define a sequential model with Conv2D layers, MaxPooling2D layers, a flatten layer, Dense layers, and a dropout layer.
4.Compile the Model: Compile the model using RMSprop optimizer.
5.Train the Model: Train the model using the fit() method. The training data and validation data is passed through the generator.
6.Make the Predictions and classification based on the test data.


