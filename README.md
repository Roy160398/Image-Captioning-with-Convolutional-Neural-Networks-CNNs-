# Image-Captioning-with-Keras
In this project we used CNN (Convolution Neural Network) model called InceptionV3 and dataset Flickr-8k.

Dataset: https://www.kaggle.com/datasets/adityajn105/flickr8k

We are using an open source dataset called Flickr-8k (containing 8000+ images). Here each image has 5 captions defining it. Now we bifurcated as follows : Training Set - 6000 images, Dev Set - 1000 images, Test Set -1000 images approx.

Convert each image into unique size fed into InceptionV3 Model of CNN.

Next we need to gather data for captions, here we make a vocabulary of all words used in captions of the images and also separate captions for Training Set.

Then we feed the Training Images and Caption Vocabulary to the model and input Test images.
