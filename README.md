# CNN-Project

The goal of this project was to create a network in TensorFlow or Keras to learn how to classify images. 

In this report the preliminary steps and results are discussed and shown. The training was done using the CIFAR-10 dataset. The CIFAR-10 dataset contains 60,000 color images size 32x32 with 10 classes. Using the architecture of your choice achieve an accuracy of at least 80%. 20 epochs will be used for each networks training. Submit the two best networks you create. 

Part 1. A 8-layer Convolutional Neural Network was created. The layers are as follows: CONV-POOL-CONV-POOL-CONV-POOL-FC-FC. Filters of size (3 x 3) are incorporated with channels of 32, 64, and 64 with a stride of 1. The pool layers will have a pooling of (2 x 2) with a stride of 2.

Part 2. A 7-layer Convolutional Neural Network was created. The layers are coded as follows: CONV-CONV-POOL-CONV-POOL-FC-FC. The filters size is (5 x 5). The channel sizes and stride will remain the same as in part 1. The previous parts pool layers and stride will also remain constant from part 1. 

The performance of both networks will be displayed with the code. 
