# Introduction to Machine Learning
## Course I - Machine Learning by Andrew NG, Standford University 
Youtube link for Machine learning with Andrew NG, Stanford University : https://www.youtube.com/playlist?list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN

### Definition
Machine learning is a field of study that gives ability to computers to learn without explicitly programming.

A computer programe learns from experience 'E' to perform a task 'T' and some performance metric 'P'. The programe improves
the performance metric 'P' with respect to the task 'T' with experience 'E'. 

---------------------------------------------------------------------------------------------------------------------------

### Supervised learning
Supervised learning problems is also called a regression problem. 

Supervised learning is the types of machine learning in which machines are trained using well "labelled" training data, and on basis of that data, machines predict the output. The labelled data means some input data is already tagged with the correct output.

In supervised learning, the training data provided to the machines work as the supervisor that teaches the machines to predict the output correctly. It applies the same concept as a student learns in the supervision of the teacher.

Supervised learning is a process of providing input data as well as correct output data to the machine learning model. The aim of a supervised learning algorithm is to find a mapping function to map the input variable(x) with the output variable(y).

In the real-world, supervised learning can be used for Risk Assessment, Image classification, Fraud Detection, spam filtering, etc.

### How Supervised Learning Works?
In supervised learning, models are trained using labelled dataset, where the model learns about each type of data. Once the training process is completed, the model is tested on the basis of test data (a subset of the training set), and then it predicts the output.

The working of Supervised learning can be easily understood by the below example and diagram:

![image](https://user-images.githubusercontent.com/62272672/173084403-fa80708d-39e8-4fed-b2f4-6352b6f87683.png)

Suppose we have a dataset of different types of shapes which includes square, rectangle, triangle, and Polygon. Now the first step is that we need to train the model for each shape.

If the given shape has four sides, and all the sides are equal, then it will be labelled as a Square.
If the given shape has three sides, then it will be labelled as a triangle.
If the given shape has six equal sides then it will be labelled as hexagon.
Now, after training, we test our model using the test set, and the task of the model is to identify the shape.

The machine is already trained on all types of shapes, and when it finds a new shape, it classifies the shape on the bases of a number of sides, and predicts the output.

### Types of supervised Machine learning Algorithms:

Supervised learning can be further divided into two types of problems:

![image](https://user-images.githubusercontent.com/62272672/173085138-b21bc55c-043d-4d95-9cbf-68309d116efb.png)

### Regression

Regression algorithms are used if there is a relationship between the input variable and the output variable. It is used for the prediction of continuous variables, such as Weather forecasting, Market Trends, etc. Below are some popular Regression algorithms which come under supervised learning:

Linear Regression

Regression Trees

Non-Linear Regression

Bayesian Linear Regression

Polynomial Regression


### Classification

Classification algorithms are used when the output variable is categorical, which means there are two classes such as Yes-No, Male-Female, True-false, etc.

Random Forest

Decision Trees

Logistic Regression

Support vector Machines

###  Advantages of Supervised learning:
With the help of supervised learning, the model can predict the output on the basis of prior experiences.
In supervised learning, we can have an exact idea about the classes of objects.
Supervised learning model helps us to solve various real-world problems such as fraud detection, spam filtering, etc.


### Disadvantages of supervised learning:
Supervised learning models are not suitable for handling the complex tasks.
Supervised learning cannot predict the correct output if the test data is different from the training dataset.
Training required lots of computation times.
In supervised learning, we need enough knowledge about the classes of object.
