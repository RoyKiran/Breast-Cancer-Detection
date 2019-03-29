# Breast-Cancer-Detection
Exploring various Machine Learning algorithms on the given Dataset

<p>This is a classification problem and the goal is to predict if the cancer diagnosis is benign or malignant based on the observations/features.</p> 

<p>Dataset: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29 OR 
 https://www.kaggle.com/uciml/breast-cancer-wisconsin-data#data.csv </p> 
 
<p>The dataset contains 30 Features with diagnosis as the target field.</p>
<br/> 
<p> We follow simple steps to solve the problem: </p>
 
 <p>
 <b>Step 1: Analyse the data</b> <br/>
 a) The dataset set good number of examples for both malignant (1) and benign (0) cases <br>
  <img src="https://github.com/RoyKiran/Breast-Cancer-Detection/blob/master/images/mb_cancer.PNG"/>
  <br>
 b) Remove unwanted features - id and Unnamed: 32 
 <br> We can definately drop least correlated or unwanted features. Since, this is a health related dataset and all the features are of concern in cancer detection. Hence, we don't prefer dropping features here. <br>
  
 c) Observe corrrelation between the features using using heatmap <br>
  <img src="https://github.com/RoyKiran/Breast-Cancer-Detection/blob/master/images/heatmap.PNG"/>
 </p>
 <p>
 <b>Step 2: Train your model </b> <br/>
  a) Here we are trying the data for most of the known models. (You can let me know, if you would like anymore to be added here) <br>
<ul><li> Ensemble Methods </li>
  <ol><li> AdaBoostClassifier </li>
      <li> BaggingClassifier </li>
      <li> ExtraTreesClassifier </li>
      <li> GradientBoostingClassifier </li>
      <li> RandomForestClassifier </li> </ol>
    </li>
    <li> Gaussian Processes - GaussianProcessClassifier </li>
   <li> Generalized Linear Model (GLM)
    <ol><li> LogisticRegressionCV </li>
        <li> PassiveAggressiveClassifier </li>
        <li> RidgeClassifierCV </li>
        <li> SGDClassifier </li>
      <li> Perceptron </li> </ol>        
    </li>
    <li> Navies Bayes
  <ol><li> naive_bayes.BernoulliNB </li>
      <li> naive_bayes.GaussianNB </li></ol>
    </li> 
   <li> Nearest Neighbor - KNeighborsClassifier </li>
   <li> Support Vector Machines (SVM)
       <ol><li> SVC </li>
       <li> NuSVC </li>
       <li> LinearSVC </li></ol>
  </li>
  <li> Trees
      <ol><li>   tree.DecisionTreeClassifier </li>
       <li> tree.ExtraTreeClassifier </li></ol> 
    </li>
    <li> XGBoost - XGBClassifier() </li></ul>
 </p>
 
