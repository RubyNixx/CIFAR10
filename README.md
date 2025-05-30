# CIFAR10 Image Classification and CNN
<b>Brief:</b>

You will develop an interactive Python notebook including the following:

## Exploratory Data Analysis and Preprocessing 

Carry out a concise EDA to familiarise yourself with the CIFAR-10 dataset. Some questions to answer are:

### Dataset Overview

- What is the shape of the training and testing datasets?
- What are the data types of the images and labels?
- How many classes are present in the dataset? What are their names?

### Distribution of Classes
•	What is the distribution of samples across the classes? Are the classes balanced or imbalanced?
4. Image Properties
•	What is the size (dimensions) of each image?
•	What is the range of pixel values in the images? Are they normalized (e.g., 0-1 or 0-255)?

### Visualization
•	Can we visualize a few random images from each class to understand their features?
•	What do these images tell us about the variation within and between classes?

## Clustering

Reduce the dimensionality of the dataset using PCA before performing the clustering. 

Split the dataset into training and testing set. Implement a classification model based on each one of the following techniques
a.	Decision tree
b.	Random forest
c.	SVM
d.	Research and implement another method such as (but not limited to)  k-Nearest Neighbours or XGBoost. I selected KNN following a literature review.

Provide detailed explanations, evaluations, and comments on the outputs of each model, demonstrating a comprehensive understanding of machine learning concepts.

##	Neural Networks: 

1.	implement and compare the performance of a shallow network and a suitable CNN
2.	Research and implement a pre-trained model such as (but not limited to) ImageNet. I selected VGG16 which is used on Imagenet - again, following literature review.

##	Hyperparameter Optimization

Select one model and demonstrate the possibility of further improving its performance using hyperparameter optimization techniques.

I selected the CNN as it performed best out of the classical & deep learning models. I experimented with the Keras Tuner and manually tuning specific classes such as bird and cat which performed worst due to having similar features.

## Results Summary and Discussion 

Provide a written and visual summary of the results obtained from the model evaluations. Clearly present the performance metrics and any insights gained from the analysis.

##	References

The key decisions in previous sections must be supported by evidence from the literature. Include primary research and relevant case studies.

## Useful Resources:

https://github.com/BIGBALLON/cifar-10-cnn

https://github.com/MadryLab/cifar10_challenge

https://github.com/davidcpage/cifar10-fast

https://github.com/tysam-code/hlb-CIFAR10

https://github.com/bitArtisan1/CIFAR10-Network-Training

https://github.com/hardiksinghal02/Final-year-project
