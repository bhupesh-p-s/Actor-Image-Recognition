# Actor-Image-Recognition
In this project we use SVM to create a machine learning model that can classify the image of five tamil actors based on the input image given. The data set is taken by batch downloading images from google it consists the images of Tamil Actors Ajith, Dhanush, Vijay, Sivakarthikeyan and Suriya.
* Here we use OpenCV to perfom data loading and cleaning operation of the images.
* We use Harr Cascades to detect the eyes and faces in the images.
* We use pywavelets to create a wavelet transform of the image and vertical stack it with the original one to analyse it.
* The we use GridSearchCV for hypertuning and finding the best model for classification
