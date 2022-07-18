This project aims to create a Deep Learning model to identify images and give the predicted labels as output. 
For the training purpose, we have used the famous CIFAR 10 dataset. The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.
Later, we created the model using tensorflow and keras environment and the model which we used was Convolutional Neural Networks. Adding to that, we used various methods like batch normalization, data augmentation and using ideal number of epochs which further helped us increasing the model's accuracy.
After training and testing, the model was able to achieve an accuracy of 89%
This was it for the Deep Learning part, next we deployed this code on a webapp using gradio platform which provides very user friendly interface wherein the user just has to provide an image as an input and the output will be its predicted class.
