# Emotion-Recognition-using-CNN
There is a lot of information that can be gained from one’s facial features and hence we can draw conclusions from those. It's pretty clear that when a person exhibits an emotion, their facial features tend to change, like the length of their lip, the distance between the eyebrows or the change in the eyes. By making a model to identify the features and what it implies by training a Convolutional Neural Network model on a given dataset. Neural Networks these days are the emerging technology and programming concept which has a wide range of applications and its very versatile. It’s almost being used in every field these days. Hence we chose that to implement our emotion recognition model. 


Steps:

1. Collecting Data and Preprocessing:
    a.  Finding the data: The dataset that is needed for this project was obtained from Kaggle.com. The dataset is Extended Cohn-Kanade Dataset.
    
   b. Preprocessing: In this step we open the dataset and traverse it through it and sort them into lists in the order depending on which class (i.e emotion in this case) do they correspond to. Then we encode the class labels so that they can be easily processed. 

2. Splitting the dataset:
In order to make sure the model is working, we split the dataset into training set, i.e the set where the model learns the features and test set where the model checks if its assumption are correct
Designing and deciding the models


 3.  Designing and deciding the network and its structure:
Since we have decided to use Convolution Neural Networks which usually comprises of different layers such as:
Convolutional Layer: This layer performs convolution operation with the input which helps in identifying the features of the input which cause the most change. 
Pooling layer: This layer helps in downsampling the output from the previous layers which is essential compressing the feature maps.
Dense layer: The neurons present in this layer receive inputs from all the neurons in the previous layer
Activation Layer: This layer applies the activation function (basically a mathematical function) to each layer and compute and give the output.
In addition to these the hyper parameters for these layers should be modified for proper output. In addition to this we can also use a
pretrained model which has worked with image classification. 
Example of such models are MobileNet, VGG16, Inception V3..etc. 

   4. Compiling the model and training the model:
  After deciding and finalising the model we choose the optimizers
  which are basically different back propagation algorithms to find
   the weights of the features. Then deciding the number of epochs 
  (the number of iterations) and the batch size we train the model and
   monitor the accuracy and loss of the model and to see if model is 
   properly fitting. These hyperparameters may be changed in order to 
   get the optimal result.


