# MNIST_w_CNN_NoOverfit_High_Accuracy
This CNN-based model uses data augmentation and dropout to get a highly accurate handwriting recognition.

What differentiates this model from many other MNIST models is it's use of data augmentation (small rotations and shifts) to control overfitting and improve generalization. The approach is also unique in that it does not use batch normalization to address overfitting, instead relying solely on dropout to do so. The final unique aspect is to keep the number of parameters as small as possible.

The model uses Tensorflow and Keras functionality (data augmentation, callbacks, etc.) and is GPU-enabled.
