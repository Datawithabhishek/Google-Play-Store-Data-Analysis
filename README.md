<h1 align='center'> :microscope: Exploratory Data Analysis On Google Play Store Apps Reviews.<h1>

![--------------------------------------------------------------------------------------------](https://github.com/andreasbm/readme/blob/master/assets/lines/grass.png)

![N|Solid](https://cdn.dribbble.com/users/5664795/screenshots/15315424/media/b39a4d06a92d81db68b6b0c479534742.gif)

## Problem Statement
The objective of this project is to explore and analyze the Google Play Store apps dataset, which includes information such as category, rating, size, and more. Additionally, a dataset containing customer reviews of the Android apps is provided. The goal is to discover key factors that contribute to app engagement and overall success.


##  💾 Project Files Description

<p>This Project includes :-
  <li>Google Colab NoteBook</li>
  <li>Project Summary (with the GitHub Repo link inside)</li>
  <li>Presentation PDF</li>
  <li>Technical Documentation</li>
</p>


### Data Source:
- [Dataset](https://drive.google.com/file/d/15SLvsarYG1wRaiZm21cC8XRfiWg0yTc1) - Dataset taken from AlmaBetter


## Features

**App Category:** Category of the app. This could be beauty, business, entertainment, education...etc.

**Rating:** How users rate the app out of 5, with 1 being the lowest rating and 5 being the highest.

**Reviews:** The number of user reviews each app has received.

**Size:** The memory size needed to install the application.

**Installs:** The number of times each application has been installed by users.

**Type:** Whether the app is free or a paid app.

**Price:** The price of the app.

**Content Rating:** This column specifies the intended audience for the app. Can be for teens, mature audience, or everyone.

**Genres:** The sub-category for each app. Example: for the Education category, this could be Education: Pretend Play, for example.

**Last Updated:** Release date of the most recent update for the app.

**Current Ver:** The app's current version.

**Android Ver:** The oldest version of Android OS supported by the app.

## 🛠️ Builds with

![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)

![NumPy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)

![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)

![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

![Seaborn](https://img.shields.io/badge/Seaborn-blue?style=for-the-badge&logo=Seaborn)

![GoogleColab](https://img.shields.io/badge/GoogleColab-orange?style=for-the-badge&logo=GoogleColab)



## Summary and Conclusion

Google Play Store is renowned as one of the largest and most popular Android app stores worldwide. With its extensive collection of apps and a wealth of data, it presents an optimal opportunity for creating effective models and identifying trends and future challenges.

In this EDA project, we utilized two raw datasets from Kaggle: one containing Play Store attributes and the other consisting of user reviews. The first dataset encompasses 13 different attributes, while the second dataset provides five additional features for data manipulation and analysis.

To ensure data integrity, we began by performing crucial data cleaning steps. This involved removing duplicate entries and dropping non-essential null values. However, due to a large number of null values in the rating column (1645), dropping them entirely would have adversely affected our final results. Therefore, we replaced these null values with the mode of ratings.

After cleaning the data, we conducted exploratory data analysis to gain a comprehensive understanding of our dataset. This involved various analyses, such as examining the number of installations for each category and exploring the correlation between app size, Android version, and the number of installs.

Furthermore, we merged both dataframes to discover correlations between the columns of the two datasets, which yielded fascinating results.

Key insights and conclusions drawn from our analysis include:
Positive correlation between reviews and installs, while price and rating exhibit negative correlation.
- The "Art and Design" category has the highest number of installs.
- Developing apps within the "Family" and "Lifestyle" categories may result in higher revenue.
- Approximately 61% of users have a positive sentiment, while only around 15% express negative sentiment.
- Free apps account for 92.12% of the dataset, while paid apps constitute 7.81%.
- The "Everyone" content rating category dominates, representing 81.80% of all apps.
- The most prevalent categories on the Play Store are "Family," "Game," and "Tools."
- "Game" category presents potential opportunities for developers due to its high number of installs.
- Popular genres for app downloads include "Tools," "Entertainment," "Education," "Business," and "Medical."
- The average rating of apps on the Play Store is 4.17, indicating a satisfactory overall quality.
- Users prefer lightweight apps and may be hesitant to download larger, paid apps.
- Apps reviewed by a larger number of people tend to be downloaded more frequently.
- Users tend to leave harsher reviews for paid apps.
- A positive correlation exists between installs and rating.
- Developing an app with a high rating requires timely updates and optimal app size.
- Developing free apps with a content rating suitable for everyone is beneficial.
- The dataset holds immense potential for improving business value and making a positive impact. - - It extends beyond the specific problem addressed in this project, with numerous other interesting possibilities waiting to be explored through further analysis.

By successfully achieving our project objectives and answering our research questions, we have obtained valuable insights into the Google Play Store apps ecosystem and the trends within.

#

Feel free to explore the repository to gain further insights into the code implementation, methodology, and findings.

Connect with me on [Linkedin](https://www.linkedin.com/in/datawithabhishek/)



Happy Learning!

#
