# standard_vs_latin
Can you distinguish standard from latin-american dancing at the Blackpool Dance Festival? Because my model can:-D
It's a binary classification task using a simple convolutional neural network. Its architecture is just 3 convolution + max pooling sets and 1 fully connected hidden layer. The training set consists of 800 images of dance couples divided into 2 classes: standard and latin. The validation set is 200 images with the same classes. 
After just 10 epochs of training it achieved around 98% on both training and validation sets. The architecture was tested using dropout, data augmentation and extra convolutions, but the accuracy was actually lower and training significantly slower. It looks like in this case simplicity works the best!
