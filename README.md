# Train CNN models with CIFAR10 on TensorFlow #

## ResNet ##

The models [18, 34, 50, 101, 152] follow the proposed architecture of the original [paper](https://arxiv.org/abs/1512.03385). To fit the CIFAR-10, I slightly modify the kernel size of `conv_1` from 7x7 to 3x3 and omit the first 3x3 max pooling layer. 

## DenseNet ##

The models [121, 169, 201, 264] follow the proposed architecture of the original [paper](https://arxiv.org/pdf/1608.06993.pdf). To fit the CIFAR-10, I slightly modify the kernel size of the front convolutional layer from 7x7 to 3x3, and omit the first 3x3 max pooling layer. 

## MobileNet V2 ##

The model basically follow the proposed architecture of the original [paper](https://arxiv.org/pdf/1801.04381.pdf). To fit the CIFAR-10, I slightly modify the strides of the front conv2d layer to 1, the strides of the second bottleneck to 1. The avgpool 7x7 has been omitted. 

