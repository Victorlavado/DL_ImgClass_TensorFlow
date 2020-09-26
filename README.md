# DL_ImgClass_TensorFlow
Convolutional Neural Network Architecture defined with TensorFlow framework. 

The architecture is based on 3 modules of batch normalization, convolutional layers
and max pooling layer. After that there is 1 dense layer that uses softmax to output
probability distributions.

The zip file of the images used to fed in the model can be downloaded here:
https://data.mendeley.com/datasets/wzr2yv7r53/1

Dataset consists on 90000 2D images of 9 different classes. Each image is
200 x 200 size RGB in .png format. 

**The main challenge of this project is to create a data generator from the folder
that stores all images**. First, it is necessary to build a dataframe that stores 
the name of the files, and the label for each of those images

**The accuracy achieved is above 90% with 20 epochs of training**, but results
can be improved using transfer learning or a deeper architecture. 

