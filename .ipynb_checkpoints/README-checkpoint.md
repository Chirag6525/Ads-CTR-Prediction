# Ads-CTR-Prediction
Ads Click Through Rate is the ratio of how many users clicked on your ad to how many users viewed your ad. For example, 5 out of 100 users click on the ad while watching a youtube video. So, in this case, the CTR of the youtube ad will be 5%. Analyzing the click-through rate help companies in finding the best ad for their target audience.

## Dataset
I found an ideal dataset for this task containing data about the user and whether the user clicked on the ad. You can download the dataset from **[here](https://www.kaggle.com/datasets/gauravduttakiit/clickthrough-rate-prediction?select=new_ad.csv)**.
- Daily Time Spent on Site: the daily timespan of the user on the website
- Age: the age of the user
- Area Income: the average income in the area of the user
- Daily Internet Usage: the daily internet usage of the user
- Ad Topic Line: the title of the ad
- City: the city of the user
- Gender: the gender of the user
- Country: the country of the user
- Timestamp: the time when the user visited the website
- Clicked on Ad: 1 if the user clicked on the ad, otherwise 0

## Random Forest Classifier
The **Random Forest classifier** is an ensemble learning method used for classification (and regression) tasks. It operates by constructing multiple decision trees during training and outputting the mode of the classes (classification) or mean prediction (regression) of the individual trees.
