
# Developing an AI application
Going forward, AI algorithms will be incorporated into more and more everyday applications. For example, you might want to include an image classifier in a smart phone app. To do this, you'd use a deep learning model trained on hundreds of thousands of images as part of the overall application architecture. A large part of software development in the future will be using these types of models as common parts of applications.

The flower data for training is provided in challenge. Trained a model using pre-trained VGG network. The goal is to test this classifier with multiple pre-trained networks like VGG, RESNET, Inception etc and also to use own pool of convolution/pooling layers. Pick the one that gives better acuuracy on validation data.



In this project, you'll train an image classifier to recognize different species of flowers. You can imagine using something like this in a phone app that tells you the name of the flower your camera is looking at. In practice you'd train this classifier, then export it for use in your application. We'll be using <a href="http://www.robots.ox.ac.uk/~vgg/data/flowers/102/index.html" target="_blank">this dataset</a> of 102 flower categories, you can see a few examples below.
![flowers](https://user-images.githubusercontent.com/35684516/51070447-4d4a9500-167c-11e9-9d7b-d5d13a42aeb9.PNG)

This script also has prediction and processing image from path to test this with different unseen flower images. The plot at the depicts top 5 predictions along with their probablity score.

# Badge
<img src="pytorch_scholarship_challenge_badge.png" width="500" height="500" >
