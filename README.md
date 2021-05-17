# Sign-Language-MNIST-classifier-CNN
In this project 28x28 dimensional images belononging to the MNIST sign language dataset have been classified into 24 classes, with 27,455 training images and 7172 test images. 
A CNN with 2 convolutional + Maxpooling layers and a Dense layer finally followed by a softmax layer was used to classify the images. Image Augmentation was done via the keras ImageDataGenerator to improve accuracy and avoid overfitting the training set. 

Final Result: After 30 epochs, we secured an accuracy of 95% on the test set. 
