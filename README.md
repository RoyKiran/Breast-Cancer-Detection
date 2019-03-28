# Breast-Cancer-Detection
Exploring various Machine Learning algorithms on the given Dataset

This is a classification problem and the goal is to predict if the cancer diagnosis is benign or malignant based on the observations/features
Dataset: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29 OR 
 https://www.kaggle.com/uciml/breast-cancer-wisconsin-data#data.csv 
 
The dataset contains 30 Features:
 id : ID number **(UNIQUE FIELD)**
 diagnosis :The diagnosis of breast tissues (M = malignant, B = benign) **(TARGET FIELD)**
 radius_mean : mean of distances from center to points on the perimeter
 texture_mean : standard deviation of gray-scale values
 perimeter_mean : mean size of the core tumor
 area_mean
 smoothness_mean : mean of local variation in radius lengths
 compactness_mean : mean of perimeter^2 / area - 1.0
 concavity_mean : mean of severity of concave portions of the contour
 concave points_mean : mean for number of concave portions of the contour
 symmetry_mean
 fractal_dimension_mean : mean for "coastline approximation" - 1
 radius_se : standard error for the mean of distances from center to points on the perimeter
 texture_se : standard error for standard deviation of gray-scale values
 perimeter_se
 area_se
 smoothness_se : standard error for local variation in radius lengths
 compactness_se : standard error for perimeter^2 / area - 1.0
 concavity_se : standard error for severity of concave portions of the contour
 concave points_se : standard error for number of concave portions of the contour
 symmetry_se
 fractal_dimension_se : standard error for "coastline approximation" - 1
 radius_worst : "worst" or largest mean value for mean of distances from center to points on the perimeter
 texture_worst : "worst" or largest mean value for standard deviation of gray-scale values
 perimeter_worst
 area_worst
 smoothness_worst : "worst" or largest mean value for local variation in radius lengths
 compactness_worst : "worst" or largest mean value for perimeter^2 / area - 1.0
 concavity_worst : "worst" or largest mean value for severity of concave portions of the contour
 concave points_worst : "worst" or largest mean value for number of concave portions of the contour
 symmetry_worst
 fractal_dimension_worst : "worst" or largest mean value for "coastline approximation" - 1 
 
 We follow simple steps to solve the problem:
 **Step 1: Analyse the data**
 a) The dataset set good number of examples for both malignant (1) and benign (0) cases
 
  
