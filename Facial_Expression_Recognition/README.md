# Facial Expression Recognition

Facial expression recognition is the task of classifying the expressions on face images into various categories such as anger, fear, surprise, sadness, happiness and so on.


#### Convolutional Neural Network
A Convolutional Neural Network (ConvNet/CNN) is a deep learning algorithm which can take in an input image, assign importance (learnable weights and biases) to various aspects/objects in the image and be able to differentiate one from the other. 
The pre-processing required in a ConvNet is much lower as compared to other classification algorithms. ConvNets have the ability to learn these filters/characteristics.
Reference - https://towardsdatascience.com/a-comprehensive-guide-to-convolutional-neural-networks-the-eli5-way-3bd2b1164a53

#### Residual Neural Networks
A residual neural network (ResNet) is an artificial neural network (ANN) of a kind that stacks residual blocks on top of each other to form a network. Residual neural networks do this by utilizing skip connections, or shortcuts to jump over some layers.
There are two main reasons to add skip connections: 
1. To avoid the problem of vanishing gradients
2. To mitigate the Degradation (accuracy saturation) problem
Reference - https://towardsdatascience.com/introduction-to-resnets-c0a830a288a4, https://arxiv.org/pdf/1512.03385.pdf 

#### Project implementation and workflow
1. Importing libraries
2. Loading dataset
3. Performing data visualization
4. Performing data augmentation
5. Building and training  model 
6. Evaluating performance of the model

It is a deep learning model based on Convolutional Neural Network(CNN or ConvNets) and Residual Blocks (ResNets) to predict Facial Expressions.



#### Some useful links
1. https://medium.com/@prudhvi.gnv/ultimate-guide-for-facial-emotion-recognition-using-a-cnn-f9239fdc63ad
2. https://medium.com/@hinasharma19se/facial-expressions-recognition-b022318d842a
3. https://medium.com/analytics-vidhya/facial-expression-detection-using-machine-learning-in-python-c6a188ac765f