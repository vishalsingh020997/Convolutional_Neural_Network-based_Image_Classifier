# A convolutional neural network-based classifier for the MNIST handwritten digit dataset with Tensorflow

the model we're going to work out in this example is:

## Model_1
Input -> CONV (-> ReLU -> Pool) -> FC -> ReLU -> FC -> Softmax -> Loss 
Accuracy = 99.07 %

## Model_2
Input -> CONV (-> RELU -> Pool) -> CONV (-> RELU -> Pool) -> FC -> ReLU -> Dropout -> FC -> Softmax -> Loss
Accuracy = 99.20 %
