This is Jyotiranjan padhi.i am a data scientist
Here i built Lenet-architechture from scratch.
# Basic Introduction
LeNet-5, from the paper Gradient-Based Learning Applied to Document Recognition, is a very efficient convolutional neural network for handwritten character recognition.
http://yann.lecun.com/exdb/publis/pdf/lecun-98.pdf

# Structure of the LeNet network
![lenet-5](https://user-images.githubusercontent.com/84494071/129846624-7cf60166-0fc5-41fd-a1a5-02035cb98382.png)

# Lenet-architechture-of-CNN

* LeNet Implement the LeNet using tensorflow to recognize handwritten number. Training with MNIST. 
* Some modifications here,  
1. Training with MNIST set with image size 28 * 28. To match the size of LeNet, Using Relu as activation function.
2. instead of Sigmod i am using softmax in output layer.
3. This net can get 99.2% correct rate on MNIST test set.
