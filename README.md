# KaggleX Data Science Project

This is a documentation on a project I undertook in the KaggleX program. 
This project is about building a Machine Learning model that detects the presence or absence of Chronic Kidney Disease (CKD) in observed patients.
In doing this I endeavor to deploy relevant Machine Learning Model techniques to aid with analysing my dataset.

# Where can data source be gotten from? #
1. Get data set (Kaggle data set/UCI Machine Learning website)
  *Note* You can explore these links to work on more practice data
   Kaggle https://www.kaggle.com/datasets
   UCL ML https://catalog.registrar.ucla.edu/course/2022/COMSCIM146?siteYear=2022
   Art and Science website https://artofstat.com/datasets
2. Neccessary libraries are imported to help us analyse the dataset
3. Performing Exploratory Data Analysis (Data set is explored to get more insights from dataset)
4. Scatter plot visualizations are build to create meaningful visualization from dataset

# Analysis
The data set outputs 0's and 1's with 0's of 115 in total representing all observations with no Chronic Kidney Disease and 1's of 43 in total representing all observations with Chronic Kidney Disease. 
For our dataset, we have a total of 158 enteries of observed patients with features such as blood pressure, albumin, specific gravity, red blood cells, white blood cells, age, pus cell, Sodium creatinine, pus cell clumps, bacteria, blood glucose random, sodium, potassium, haemoglobin, anemia, coronary artery disease, diabetes mellitus, appetite, class, blood urea, age, etc

# Machine Learning Models (Before Model Deployment)

1. Before machine learning models are built, let us look at a process flow which takes place
![image](https://github.com/martfem13/KaggleX_Data-Science_Project/assets/94946814/c1594440-e459-47b4-9ae5-d566925bafca)

In our dataset, there are the x-cordinates and the y-cordinates. We choose the K-nearest classifier to train our labeled data on.
Scatterplots were analyzed using an intuitive strategy. K-nn with a k-value of 3 is used to train and test model to make predictions on the new data points.

See code for full content to ckd prediction code 

