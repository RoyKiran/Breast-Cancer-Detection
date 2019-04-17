# Breast-Cancer-Detection
Exploring various Machine Learning algorithms on the given Dataset

<p>This is a classification problem and the goal is to predict if the cancer diagnosis is benign or malignant based on the observations/features.</p> 

<p>Dataset: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29 OR 
 https://www.kaggle.com/uciml/breast-cancer-wisconsin-data#data.csv </p> 
 
<p>The dataset contains 30 Features with diagnosis as the target field.</p>
<br/> 
<hr>
<div>
<p> Hereby we follow simple steps to solve the problem: </p>
 <p> <b>Step 1: Read the dataset </b></p>
 <p>
 <b>Step 2: Analyse the data</b> <br/>
 a) Check target feature - As seen from the graph below, the dataset has good number of examples for both malignant (1) and benign (0) cases <br>
  <img src="https://github.com/RoyKiran/Breast-Cancer-Detection/blob/master/images/mb_cancer.PNG"/>
  <br>
 b) Remove unwanted features - id and Unnamed: 32 
 <br> We can drop least correlated or unwanted features and then train our model accordingly. But since this is a health related dataset and so I'm considering that all the features here are of concern in cancer detection. Hence, we don't prefer dropping any of the features here. <br>
  
 c) Observe corrrelation between the features and Normalize the dataset <br>
  <img src="https://github.com/RoyKiran/Breast-Cancer-Detection/blob/master/images/heatmap.PNG"/>
 </p>
 <p>
 <b>Step 3: Train your model </b> <br/>
  a) Here we are trying the data for most of the known models. (You can let me know, if you would like anymore to be added here) <br>
<ul><li> Ensemble Methods 
  <ol><li> AdaBoostClassifier </li>
      <li> BaggingClassifier </li>
      <li> ExtraTreesClassifier </li>
      <li> GradientBoostingClassifier </li>
      <li> RandomForestClassifier </li> </ol> </li>
   <li> Gaussian Processes - GaussianProcessClassifier </li>
   <li> Generalized Linear Model (GLM)
     <ol><li> LogisticRegressionCV </li>
        <li> PassiveAggressiveClassifier </li>
        <li> RidgeClassifierCV </li>
        <li> SGDClassifier </li>
        <li> Perceptron </li> </ol>    </li>     
   <li> Navies Bayes 
     <ol><li> naive_bayes.BernoulliNB </li>
     <li> naive_bayes.GaussianNB </li></ol>  </li>
   <li> Nearest Neighbor - KNeighborsClassifier </li>
   <li> Support Vector Machines (SVM) 
      <ol><li> SVC </li>
      <li> NuSVC </li>
      <li> LinearSVC </li></ol> </li>
   <li> Trees
      <ol><li> DecisionTreeClassifier </li>
      <li> ExtraTreeClassifier </li></ol>  </li>
   <li> XGBoost - XGBClassifier </li></ul>
 </p>
 <p>
 b) Tune the selected model <br> 
 Tune the base model by tuning the parmeters. You can set the value of parameters as much as you want as long as it is within it's required range.
 Here we are training our dataset with below model : (Let me know if any more should be added here)
<ol><li> SVM </li>
 <li> LinearSVM </li>
 <li> GaussianProcessClassifier </li>
 <li> ExtraTreesClassifier </li> 
 <li> Xgboost Classifier</li> 
 <li> GaussianNB </li>
 <li> BaggingClassifier </li>
 <li> QuadraticDiscriminantAnalysis </li>            
 </ol>
</div>

<hr>
<p>  You can find the script on <a href="https://www.kaggle.com/roykiran/breast-cancer-detection/">Kaggle </a> as well.</p>
<p> Here my aim is to show the various tunning parameters of an algorithm and as and when I get time, i will keep updating them till I find the best one :) </p>
