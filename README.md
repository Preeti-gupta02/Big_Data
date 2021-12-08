# Big_Data
ProblemSet 1
Part 1 and Part 2 would give you an insight on using pandas.
Part 3 will focus on cleaning the dataset for missing datapoints.
Part 4 and Exercise 5 would involve generating graphs based on the traffic dataset.

ProblemSet 2 
Load the Iris Dataset
Implement Standard Scalar based feature extraction
Implement PCA and use all components and compute the explained variance of each PCA component
Implement PCA and use two components that explain maximum variance. Implement logistic regression model to train and test and give a visual display of the performance by showing a plot of the decision regions along with the test data. Print the test accuracy.

ProblemSet 3
Task 1
Convert the features in a form that can be given as input to tensorflow library/functions
In this task I will perform data augmentation. That is, pre-process the data to make the model more robust. Most common data augmentation techniques are rotation, flips and histogram equalization. You can choose an augmentation technique of your choice.

Task 2
Try to build a Neural Network model, train on the features and report the accuracy. Report your observations on the time taken on GPU and TPUs.
Create a CNN based model with 5 hidden layers and 100 hidden units each layer.
Create an LSTM based model with 2 hidden layers and 1024 hidden units in each layer.

ProblemSet4
This guide trains a neural network model to classify images of clothing, like sneakers and shirts. This guide uses tf.keras, a high-level API to build and train models in TensorFlow.

Project 1:
This project consists of 4 questions:

Create an RDD with kaggle_visible_evaluation_triplets.txt and replace the song name with the song index from kaggle_songs.txt. Identify the number of songs that do not have any rating.
Generate song ratings based on the song play count as a normalized score between 0 and 1.
Identify the popular song based on this rating and recommend songs to user, given user id based on the algorithm used in Movie recommender system from class.
Using Cosine similarity function, identify pair-wise similarity between each pair of users and generate the top 5 most similar users without an overlap in users.

Project 2
This task is split into multiple parts:

Print the Histogram of variable 'Primary Type'. The x-axis should be each primary type, and the y-axis will be the count of each Primary type.
Sort the histogram in decreasing order. This will help you to understand which Primary Type of crime occured more than the rest.
Now, 'K' is the total number of classes in Primary Type. Experiment with K=2,3,4,5 as the most popular Primary Type data to be used and predicted.
For a given K, filter the dataset to extract the most popular K Primary Types and report what percentage of the total dataset this amounts to. Lets call this percentage, F. Now, find what fraction of this filtered data can be supported in your analysis on your local machine. Lets call this P. For example, of the approximately 7 million entries, say for K=3, we find that the top three types of crime add up to around 3.5 million, which makes F be 50%. Now see if your machine can handle all 3.5 million entries in you ML analysis. Say you find out that you can only handle 60% of this, which means your working dataset will be 2.1 million entries.
For each K=2,3,4,5 (and associated percentage 'P'), you should train a model and report the accuracy. (Refer to other tasks)

Project 3:
In this Project, we will work with CIFAR10 image dataset. Test the project on Google Colab running on a CPU, GPU and TPU

