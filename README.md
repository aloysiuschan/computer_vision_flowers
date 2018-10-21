# computer_vision_flowers
The Jupyter notebook contains code to design, train, and evaluate a CNN (convolutional neural network) that recognizes images of different species of flowers (daisy, dandelion, rose, sunflower, tulip). The data was obtained from https://www.kaggle.com/alxmamaev/flowers-recognition, and contains 4323 images of the various species of flowers, out of which I assigned 250 images to the test set for evaluation purposes.

I designed the CNN using the Keras library. Apart from the convolution, pooling, and fully-connected layers, I also introduced two dropout layers to avoid overfitting the model. In addition, I augmented the number of images with transformed (e.g. zoomed, sheared) versions of those images. After training the CNN for 3 epochs, it managed to achieve a test accuracy of 75%.
