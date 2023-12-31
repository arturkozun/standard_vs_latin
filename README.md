# standard_vs_latin
Can you distinguish between standard and Latin-American dancing at the Blackpool Dance Festival? Because my model can! 

It's a binary classification task using a simple convolutional neural network. Its architecture comprises 3 sets of convolution and max pooling, along with 1 fully connected hidden layer. The training set consists of 800 images of dance couples (sized 133x200), divided into 2 classes: standard and Latin. The validation set also includes 200 images with the same classes. 

After just 10 epochs of training, it achieved around 98% accuracy on both the training and validation sets. Although the architecture was tested using dropout, data augmentation, and extra convolutions, the accuracy actually decreased and the training became significantly slower. It seems that in this case, simplicity works best!

![66__41384_641338__98945](https://github.com/arturkozun/standard_vs_latin/assets/108707614/bde31fa1-0cd1-4dae-935d-2381c24d4dfe)
![67__41384_641333_1482_SZAR8960](https://github.com/arturkozun/standard_vs_latin/assets/108707614/426242fd-f31c-4923-893a-29f10f9ff39c)
