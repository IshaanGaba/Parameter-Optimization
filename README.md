# Parameter-Optimization

### About SVM and Parameter Optimization
Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.

Some of the most important parameters of SVM such as kernel, C, and gamma can be changed in order to achieve a higher accuracy. This is called as Hyperparameter Tuning.


In this python file, I've used a Fitness Function to optimize the parameters.

### Dataset
The dataset for the project has been downloaded from the UCI Machine Learning Repository.
https://archive.ics.uci.edu/ml/datasets/Room+Occupancy+Estimation

This dataset is used for estimating the precise number of occupants in a room using multiple non-intrusive environmental sensors like temperature, light, sound, CO2 and PIR. It is a multi-variate classification Dataset.

Number of Instances: 10129

Number of Attributes: 16

### Final Result Table

| Sample | Best Accuracy | Best Kernel | Best Nu | Best Epsilon |
|--------|---------------|-------------|---------|--------------|
|   1    |      0.90     |    poly     |  9.62   |     2.10     |
|   2    |      0.95     |   linear    |  3.82   |     4.57     |
|   3    |      0.97     |   linear    |  5.85   |     8.51     |
|   4    |      0.92     |    poly     |  4.79   |     1.37     |
|   5    |      0.86     |    poly     |  6.63   |     4.67     |
|   6    |      0.81     |   sigmoid   |  5.69   |     5.11     |
|   7    |      0.87     |   linear    |  7.67   |     9.80     |
|   8    |      0.91     |    poly     |  6.99   |     2.65     |
|   9    |      0.91     |    poly     |  2.45   |     6.31     |
|   10   |      0.82     |    poly     |  0.83   |     1.31     |



### Convergence Graph

![image](https://github.com/IshaanGaba/Parameter-Optimization/blob/7928870df3e0d6caa85bf5ac0a7c323fe9243719/graph.png)


### Result
From the above graph, we can conclude that the model is well trained and parameter have been optimized due to the less gap between training and cross-validation curve.

The graph is made for the sample which has best accuracy. Sample 3 has the best accuracy of 0.97 having kernel = linear, Nu = 5.85 and Epsilon = 8.51.
