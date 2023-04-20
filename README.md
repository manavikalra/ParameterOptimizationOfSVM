# ParameterOptimizationOfSVM

Assignment for UCS654

## About SVM and Parameter Optimization
Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.

Some of the most important parameters of SVM such as kernel, C, and gamma can be changed in order to achieve a higher accuracy. This is called as Hyperparameter Tuning.

We can perform this task using GridSearchCV for optimizing these parameters.

In this python file, I've used a Fitness Function to optimize the parameters.

## Dataset
The dataset for the project has been downloaded from the UCI Machine Learning Repository. https://archive.ics.uci.edu/ml/datasets/Bias+correction+of+numerical+prediction+model+temperature+forecast

This data is for the purpose of bias correction of next-day maximum and minimum air temperatures forecast of the LDAPS model operated by the Korea Meteorological Administration over Seoul, South Korea. This data consists of summer data from 2013 to 2017. The input data is largely composed of the LDAPS model's next-day forecast data, in-situ maximum and minimum temperatures of present-day, and geographic auxiliary variables. There are two outputs (i.e. next-day maximum and minimum air temperatures) in this data. Hindcast validation was conducted for the period from 2015 to 2017.

Number of Instances: 7588

Number of Attributes: 27

## Final Result Table
<img width="534" alt="Screenshot 2023-04-20 at 6 24 03 AM" src="https://user-images.githubusercontent.com/79714473/233229996-06c2412d-846e-4926-8def-d0a1adbd1fc3.png">


## Convergence Graph
![image](https://user-images.githubusercontent.com/79714473/233229610-83e947de-0bf2-4410-ba82-26f4497f69af.png)


## Discussion
From the above graph, we can conclude that the model is well trained and parameter have been optimized due to the less gap between training and cross-validation curve.

The graph is made for the sample which has best accuracy. Sample 1 has the best accuracy of 0.94 having kernel = Linear, Nu = 5.92 and Epsilon = 7.25.

## Written By
Name : Manavi Kalra

Roll No. : 102003368

Sub-Group: 3CO15
