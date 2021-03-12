---
title: Wine quality report
date: 2021-01-18T12:58:17.000+06:00
image: images/blog/wine.jpg
feature_image: images/blog/wine-1.png

---
### The main objective of the analysis

➢ The main objective of this model is to predict the quality of wine

### Brief description of the data set and a summary of its attributes.

➢ The dataset chosen for this report was red wine quality from the UCI repository   
➢ There are 12 attributes: -   
▪ fixed acidity   
▪ volatile acidity   
▪ citric acid   
▪ residual sugar   
▪ chlorides   
▪ free sulfur dioxide   
▪ total sulfur dioxide   
▪ density   
▪ pH   
▪ sulphates   
▪ alcohol   
▪ Output variable (based on sensory data): quality (score between 0 and 10)

### Brief summary of data exploration and actions are taken for data cleaning and feature engineering.

➢ There were no null values and the data set was perfectly clean

### Summary of training

➢ I used the following classification method for choosing the best model suitable for this
problem: -   
♦ Logistic regression   
♦ KNN classifier   
♦ Decision tree   
♦ Pruned decision tree   
♦ Random forest   
♦ Support vector machine with 4 different kernels   
♦ AdaBoost   
♦ Gradient boost   
♦ Bagging   
♦ Naïve Bayes

### Insights derived from these models.

➢ The best model for this dataset was random forest because it has the most accuracy of 80 compared to other models at a 95% confidence level.   
➢ The classification report also shows that it has a higher F1 score and good recall and precision compared to other models

### Suggestions for the next steps in analyzing this data, which may include suggesting revisiting this model adding specific data features to achieve a better explanation or a better prediction.

➢ This model can be further improved by Hyperparameter tuning   
➢ The PCA approach can also help in improving the accuracy further   
➢ This model can also be compared with other algorithms like Gridsearch CV or Randomsearch CV etc.

\[[PDF](https://github.com/VIMALRANJEEV/my_work/blob/master/IBM/wine_quality/Wine_classification_Report.pdf)\]