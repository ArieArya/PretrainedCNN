# Pre-trained Convolutional Neural Network for Image Classification

This project is part of the IBM AI Engineering Specialization Capstone project, and involves building a pre-trained convolutional neural network for simple image classification of concrete images. In particular, it utilizes the Resnet50 and VGG16 pre-trained models in Keras, and replaces its topmost layer with a dense output layer of 2 neurons for the binary classification of concrete images (i.e. whether the concrete is cracked or uncracked).

The example of the concrete images are shown below:
<img src='/concrete_data/test/positive/19751.jpg' width="60%">
<img src='/concrete_data/test/negative/19751.jpg' width="60%">

The neural networks are trained with over 40,000 concrete images, and achieves a binary classification test accuracy of 100% and 99.8% for the Resnet50 and VGG16 respectively. Note as the image file sizes are large, only a small sample of images for the training, test, and validation sets are provided here.
