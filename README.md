# Parameter-Optimization

About SVM and Parameter Optimization
Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.

Some of the most important parameters of SVM such as kernel, C, and gamma can be changed in order to achieve a higher accuracy. This is called as Hyperparameter Tuning.


In this python file, I've used a Fitness Function to optimize the parameters.

Dataset
The dataset for the project has been downloaded from the UCI Machine Learning Repository.
https://archive.ics.uci.edu/ml/datasets/Room+Occupancy+Estimation

This dataset is used for estimating the precise number of occupants in a room using multiple non-intrusive environmental sensors like temperature, light, sound, CO2 and PIR. It is a multi-variate classification Dataset.

Number of Instances: 10129

Number of Attributes: 16

Final Result Table



Convergence Graph
graph ![image](https://github.com/palakga-rg/Parameter_Optimization_SVM/assets/108742298/0396eefe-a280-491d-a014-e652c8b1c465)


Discussion
From the above graph, we can conclude that the model is well trained and parameter have been optimized due to the less gap between training and cross-validation curve.

The graph is made for the sample which has best accuracy. Sample 9 has the best accuracy of 0.97 having kernel = Poly, Nu = 1.27 and Epsilon = 6.87.
