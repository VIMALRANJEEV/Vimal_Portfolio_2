---
title: Facebook data analysis report
date: 2020-11-09T13:45:06.000+06:00
image: images/blog/Facebook.png
feature_image: images/blog/facebook-1.png

---
### Brief description of the data set and a summary of its attributes.

Title: Facebook performance metrics.  
Sources: Created by: Sérgio Moro, Paulo Rita and Bernardo Vala (ISCTE-IUL) @ 2016   
Past Usage: The full dataset was described and analyzed in S. Moro, P. Rita and B. Vala.

Relevant Information: The data is related to posts' published during the year 2014 on Facebook's page of a renowned cosmetics brand. This dataset contains 500 of the 790 rows and part of the features analyzed by Moro et al. (2016). The remaining were omitted due to confidentiality issues.   
Number of Instances: 500   
Number of Attributes: 19   
I got this dataset from UCI public dataset.

### Summary of attribute:

Page total likes: This attribute shows the total number of likes pages have received   
Category: To identify the category of the page   
Post Month: Month of the post   
Post Weekday: Day on which the post was uploaded   
Post Hour: Identifies the post time   
Paid: Whether paid for promotion or not   
Lifetime Post Total Reach: Total reach of each post in a lifetime.   
Lifetime Post Total Impressions: Total number of people who saw the post.   
Lifetime Engaged Users: Total number of people who clicked on post   
Lifetime Post Consumers: total number of people who saw your post and bought something.   
Lifetime Post Consumptions: Total number of people who visit your post   
Lifetime Post Impressions by people who have liked your Page   
Lifetime Post reach by people who like your Page: reached to other people by people who
liked the post.   
Lifetime People who have liked your Page and engaged with your post: Regular visitors of
the post.   
Comment: Total number of comments for each post   
Like: number of likes for each post   
Share: number of share(forwards) of the post.   
Total Interactions: Total number of people who have interacted with the post. \\

### The initial plan for data exploration

The plan for data exploration was to first identify the data types of attributes.   
Then identifying the mean, median, minimum, maximum and the IQR of each attribute.   
Late the attributes were visualized using distribution plot, box plot(for identifying outliers) and count plots according to data types of the attributes.

### Actions are taken for data cleaning and feature engineering

The data was cleaning by filling the missing values with the mean of the columns and the outliers were bought to 3rd interquartile values of the columns

\[[PDF](https://github.com/VIMALRANJEEV/my_work/blob/master/IBM/Facebook/Report.pdf)\]