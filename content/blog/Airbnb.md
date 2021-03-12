---
title: Airbnb cost prediction report
date: 2020-11-30T13:32:54.000+06:00
image: images/blog/airbnb.png
feature_image: images/blog/airbnb-1.jpg

---
### Objective

➢ The main objective of this model is to predict the prices of apartments in New York City on Airbnb.

### Brief description of the data set and a summary of its attributes.

➢ The dataset chosen for this report was Airbnb’s open dataset from 2019 house listing in New York City.  
➢ The dataset has 16 following attributes: -   
▪ Name: Name of the apartment   
▪ Id: serial number for the data   
▪ Host_name: The name of the person or organization to which the apartment belongs.  
▪ Host_id: uniquenumer oided to the host   
Latitude and longitude: for the position of apartments on map.   
▪ neighbourhood grup: area to which the apartment is located.   
▪ Neighbourhood: Area in which apartment is located   
▪ room_type: Listed room types   
▪ pice: Price of the room   
▪ minimum_nights: Amount of nights stayed   
▪ number_of_reviews   
▪ last_review: Latest review date   
▪ reviews_per_month: number of reviews per month   
▪ calculated_host_listings_count: amount of listing per host   
▪ availability_365: number of days when listing is available for booking 

### Brief summary of data exploration and actions that are taken for data cleaning and feature engineering.

➢ The null values were cleaned by applying the mean values to them.   
➢ The datatype of last_review was changed to DateTime for more understanding.

### Summary of training

➢ The dataset was split into 70:30 ie, 70% for training and 30% for testing.   
➢ Linear regression:   
❖ Mean squared error:39962614951181760.00000   
❖ Coefficient of determination:-664107546751.53162   
➢ Ridge regression:   
❖ 53649.20341   
❖ Coefficient of determination:0.10845   
➢ Lasso regression:   
❖ Mean squared error: 56027.12505   
❖ Coefficient of determination: 0.06893   
➢ Cross validation:   
Cross-validation score of linear regression =-492005747090.12537   
Cross-validation score of ridge regression = 0.10921   
Cross-validation score of lasso regression = 0.07121

### The final model that best fits the needs in terms of accuracy and explainability.

➢ The model chosen for this dataset is ridge regressor due to the reason that it takes more features into account and has a better overall performance compared to the other two models.

### Summary Key Findings and Insights

➢ The key findings that I saw from my linear regression model were even though it highly simple most of the time it is inefficient this due to the fact that in this dataset all the point where scatter and the dimensionality was high due to this reason fitting, a simple straight line was not possible.   
➢ The mean squared error value is very high indicating that the straight line is pass through very fewer points.   
➢ The negative cross-validation score shows that the model is struggling to find a relationship to find between the features and produce a straight line.

### Suggestions for next steps in analyzing this data, which may include suggesting

revisiting this model adding specific data features to achieve a better explanation or
a better prediction.
➢ The next step of improving this model would be to consider other models like
decision tree regressor, random forest regressor etc.   
➢ The model could also be improved by hyperparameter tuning.   
➢ Finding the important feature using feature importance can also improve the
model a lot.

\[[PDF](https://github.com/VIMALRANJEEV/my_work/blob/master/IBM/Airbnb/IBM-report-supervised.pdf)\]