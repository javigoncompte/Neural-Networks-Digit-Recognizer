# Kaggle Image Digits Recognizer

predict which digit is from the images
Keras Tensorflow was used as the deeplearning framework
Did same model building only using Tensorflow without Keras

## Features use to do prediction

Pixels of each image, 


### Model Used
Convolution neural network
Activation relu, added two dense layers with size of of the x_train index so number of pixels, dropped half first and then 1/3 added a extra layer of 10 with activation softmax
loss was categorical crossentropy optimizer adam and metrics was accuracy.
```
