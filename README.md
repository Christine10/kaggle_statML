# kaggle_statML
<br>
# Problem : https://www.kaggle.com/c/ifood-rice/overview <br>
# Description: <br>
The goal of our project was to accurately classify food images into 251 possible classes. The dataset was
provided by Kaggle which consisted of 118,475 images collected from the web. They also provided humanverified labels for both validation set of 11,994 images and the test set of 28,377 images. Automatic food classification assists food intake monitoring in order to maintain a healthy diet. Food classification can be challenging as there are a large number of classes and many of them appear to be visually similar. In our work, we explored several Convolutional Neural Network (CNN) architectures in order to solve this problem. Data
Pre-processing and Augmentation techniques was also performed to enhance performance.
<br>
# Results
We adopted Transfer Learning in our modelling and pre-trained models on the ImageNet dataset. We trained the models in two stages. In the first phase, we freeze the body weights and only train the head. This is done to convert analyzed features into predictions of our own data. In the second stage, we unfreeze the layers of the backbone and fine-tune the whole model. 
