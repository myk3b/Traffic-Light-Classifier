# Traffic-Light-Classifier
Build a Image Classifier From Scratch
Traffic_Light_Classifier
March 15, 2020

0.1    # Traffic Light Classifier
In this project, you’ll use your knowledge of computer vision techniques to build a classifier for 
images of traffic lights! You’ll be given a dataset of traffic light images in which one of three 
lights is illuminated: red, yellow, or green.
In this notebook, you’ll pre-process these images, extract features that will help us distinguish 
the different types of images, and use those features to classify the traffic light images into 
three classes: red, yellow, or green. The tasks will be broken down into a few sections:

1.  Loading and visualizing the data.  The first step in any classification task is to be familiar 
with your data; you’ll need to load in the images of traffic lights and visualize them!
2.  Pre-processing. The input images and output labels need to be standardized. This way, you can 
analyze all the input images using the same classification pipeline, and you know what output to 
expect when you eventually classify a new image.
3.  Feature extraction. Next, you’ll extract some features from each image that will help distin- 
guish and eventually classify these images.
4.  Classification and visualizing error.  Finally, you’ll write one function that uses your fea- 
tures to classify any traffic light image.  This function will take in an image and output a label. 
You’ll also be given code to determine the accuracy of your classification model.
5.  Evaluate your model. To pass this project, your classifier must be >90% accurate and never 
classify any red lights as green; it’s likely that you’ll need to improve the accuracy of your 
classifier by changing existing features or adding new features. I’d also encourage you to try to 
get as close to 100% accuracy as possible!

Here are some sample images from the dataset (from left to right: red, green, and yellow traffic 
lights):
0.1.1    Here’s what you need to know to complete the project:
Some template code has already been provided for you, but you’ll need to implement additional code 
steps to successfully complete this project.  Any code that is required to pass this project is 
marked with ’(IMPLEMENTATION)’ in the header.  There are also a couple of questions about your 
thoughts as you work through this project, which are marked with ’(QUESTION)’ in the
header.  Make sure to answer all questions and to check your work against the project rubric to 
make sure you complete the necessary classification steps!
Your project submission will be evaluated based on the code implementations you provide, and  on  
two  main  classification  criteria.   Your  complete  traffic  light  classifier  should  have:   
1. Greater than 90% accuracy 2. Never classify red lights as green
