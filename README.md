# Convolutional-Neural-Network

Handwritten Digit classification using MNIST dataset. MNIST is a dataset of 60,000 training set images of handwritten single digits between 0 and 9, each image is a 28x28 pixel square.

Using CNN to classify a given image of a handwritten digit into one of 10 classes representing integer values from 0 to 9, inclusively.
Steps:
- Do Preprocessing step (Normalization). Rescale pixel values to the range [0-1].
     Convert Datatype of pixels to float
     Divide each image by 255.
- Build a 4 different architecture convolutional neural network model that can detect the digit of a given image. (change number of convolutional layer, pooling layers, ...)
- Apply cross validation during training. The training dataset is shuffled prior to being split.
- Evaluate models using accuracy.
