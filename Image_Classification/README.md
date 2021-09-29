# Image Classification using Transfer Learning

Image Classification is a  task that attempts to understand an entire image. The goal is to classify the image by assigning it to a specific label. This requires a lot of training data and computation resources. Many companies find it difficult to train a good image classification model because of such huge computation requirement. Therefore, one of the emerging techniques that overcomes this barrier is the concept of transfer learning.

#### Transfer Learning
Transfer learning involves taking a pre-trained model, extracting one of the layers, then taking that as the input layer to a series of dense layers. This pre-trained model is usually trained by institutions or companies that have much larger computation and financial resources. Some of these popular trained models for image recognition tasks are VGG, Inception and ResNet.
Using this newly formed model, we can then set the parameters within the pre-trained model to be non-trainable while only optimizing the parameters of the subsequent dense layers during training.

#### Project implementation and workflow:
Following are the sub-steps:
1. Importing libraries
2. Data generators
3. Callback
4. Plot result
5. CNN model
6. Model summary
7. Fitting model
8. Plotting training and validation results
9. Download model weights, import model, load weights into model
10. Set layers to be non-trainable for pre-trained model
11. Model summary of Inception v3
12. Obtain last layer output of the pre-trained model
13. Adding dense layers after pre-trained model
14. Model summary of Inception v3 with dense layers
15. Fitting model
16. Plotting training and validation results

In this project, I am performing the task of Image Classification using the EfficientNetB0 pre-trained network.




#### Some useful links on Transfer Learning:
1. https://medium.com/@saket.srivastawa/image-classification-using-transfer-learning-49411ececf5d
2. https://medium.com/analytics-vidhya/multi-class-image-classification-using-transfer-learning-with-deep-convolutional-neural-networks-eab051cde3fb
3. https://medium.com/@prakhosha/tensorflow-image-classification-using-transfer-learning-for-beginners-e1bd94ccfcca
4. https://arxiv.org/abs/1409.4842