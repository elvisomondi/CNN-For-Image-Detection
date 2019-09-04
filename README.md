# Convolutional Neural Network For Image Recognition
This convolutional neural network uses the keras and the tensorflow backend.  It has been trained on 8000 images of cats and dogs. Given an image of a cat or a dog, it can give an accurate prediction of what the object in the image is.

![alt text](https://uploads.disquscdn.com/images/f41ae53793c34e5470cb45d58674178855f50bb9521cc903eeca148954991c78.jpg)

**Convolutional Neural Networks**
**An input image is used** <br>
    • A feature detector is scanned over the image and maps the results to a feature map.
   <br> • Usually the feature detector is a 3x3 grid.
Main objective of convolution is to find features in an image. 


**ReLu (Rectifier Function)** <br>
    • Relu is used to increase non linearity in the network, because images are non linear
Max Pooling<br>
   <br> • Mapping the maximum value in a feature detector to that even if the maxium value is on a different index of the detector of a stride, it Is still maps the maximum value to the feature map.
  <br>  • This reduces the size of the map by 75 percent.
   <br> • Preventing overfitting
   <br> • Why max pooling? http://ais.uni-bonn.de/papers/icann2010_maxpool.pdf

**Flattening**
  <br>  • Pooled feauture map is flattened, meaning the numbers in the pool are taken row by row and put in to a column.
  <br>  • These are then used in a ANN