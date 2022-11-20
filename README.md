# Project - Google Play Store apps and reviews Analysis

In this project, I conducted a comprehensive analysis of the Android app market by comparing over ten thousand apps in Google Play across different categories.It involved data cleaning, correcting data types, exploring app categories, and obtaining a distribution of app ratings. These steps then helped in drawing insights about the app size and app prize, and this relationship was analyzed using jointplots.

## About the Datasets

I have used two different datasets (courtesy of Datacamp).

1. **‘apps.csv’** contains all the details of the apps on Google Play. These are the features that describe an app.

2. **‘user_reviews.csv’** contains 100 reviews for each app, most helpful first. The text in each review has been pre-processed, passed through a sentiment analyzer engine and tagged with its sentiment score. 

## Key Findings

**Business Question that I try to answer: "Perform a comprehensive analysis of the Android app market by comparing over ten thousand apps in Google Play across different categories and look for insights in the data to devise strategies to drive growth and retention."**

These are some of the key findings for this project:
1. We will see that there are *33* unique app categories present in our dataset.

2. **Family** and **Game** apps have the highest market prevalence. Interestingly, **Tools**, **Business** and **Medical** apps are also at the top.

3. Ratings are a key performance indicator of an app. The average volume of ratings across all app categories is *4.17*.

4. The histogram plot is skewed to the left indicating that the majority of the apps are highly rated with only a few exceptions in the low-rated apps.
   <br> </br>
   ![app_ratings](https://user-images.githubusercontent.com/75243291/202888380-69ad6b11-685b-4573-b7d4-69a90adaef80.png)

 
