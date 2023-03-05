# Play-Store-App-Review-Analysis-EDA
 
![image.png](https://cdn.dribbble.com/users/5172733/screenshots/12297434/media/f499f213ff694916468aa5aa5ad7e6ec.gif)

## Introduction 📖
Google Play Store or formerly Android Market, is a digital distribution service developed and operated by Google. It is an official apps store that provides variety content such as apps, books, magazines, music, movies and television programs. It serves an as platform to allow users with 'Google certified' Android operating system devices to donwload applications developed and published on the platform either with a charge or free of cost. With the rapidly growth of Android devices and apps, it would be interesting to perform data analysis on the data to obtain valuable insights.

## Problem Description 🤔  
The Play Store apps data has enormous potential to drive app-making businesses to success. Actionable insights can be drawn for developers to work on and capture the Android market. Each app (row) has values for catergory, rating, size, and more. Another dataset contains customer reviews of the android apps. Explore and analyze the data to discover key factors responsible for app engagement and success.

### The contents of Play Store Data are:
* **App:** Name of the app.
* **Category:** Category of the app. Some examples are: ART_AND_DESIGN, FINANCE, COMICS, BEAUTY etc.
* **Rating:** The current average rating (out of 5) of the app on Google Play.
* **Reviews:** Number of user reviews given on the app.
* **Size:** Size of the app in MB (megabytes).
* **Installs:** Number of times the app was downloaded from Google Play.
* **Type:** Whether the app is paid or free.
* **Price:** Price of the app in US$.
* **Content Rating:** A content rating (also known as maturity rating) rates the suitability of TV broadcasts, movies, comic books, or video games to its audience.To   show which age group is suitable to view media and entertainment.
* **Genres:** A category of artistic, musical, or literary composition characterized by a particular style, form, or content.
* **Last Updated:** Date on which the app was last updated on Google Play.
* **Current Ver:** Current Version means a version of the software that is currently being supported by its publisher.
* **Android Ver:** Android versions (codenames) are used to describe the various updates for the open source Android mobile operating system.


### The contents of User Reviews are:
* **App:** Name of the app on which the user review was provided. Matches the App column of the play_store_data.csv file
* **Translated Review:** The pre-processed user review text.
* **Sentiment:** Sentiment category of the user review - Positive, Negative or Neutral.
* **Sentiment Polarity:** Sentiment score of the user review. It lies between [-1,1]. A higher score denotes a more positive sentiment.

## The series of steps followed in this project 📃

	1. Importing Packages
	2. Reading Data
	3. Explore the structure of the Datasets
	4. Cleaning the Given Datasets
	5. Convert the Installs, Price and Size columns for EDA analysis
	6. Preparing User_review data frame for EDA
	7. Exploratory Data Analysis (EDA)
	8. ED Analysis for Paid Apps
	9. Data Visualization of user_review Dataframe
	
## The tools that are going to be used for this EDA would be 💾
    1. Numpy 
	2. Pandas
	3. Matplotlib 
	4. Seaborn

which I have learnt from the course.

## CONCLUSION ✌

### We have analyzed a variety of parameters as part of this study to analyse play store applications that would help AlmaBetter launch their apps successfully. In order to give them the best results from our study, we concentrated more on the problem statements and data cleaning in the initial phase.

### based on analysis, there is minimal information available regarding the play store datasets

* 92% of apps are available for free in play store.
* There are 33 categories in the dataset as a whole. The majority of Play Store apps fall under the FAMILY & GAME category.
* Most of the apps in the Google Play store are available to everyone.
* The genres of tools, entertainment, and education make up the great majority of apps in the Google Play Store.
* The majority of apps in the Google Play Store run on Android 4.1 or later.

### I would advise anyone creating an app for the Playstore to follow these standards.

**Category**
* Communication
* Social 
* Video Players
* Entertiment  
* Productvity

**Content Rating**
* Teen
* Everyone 10+

**Geners**
* Communication
* Social
* Video Players & Editors
* Arcade
* Adventure; Action & Adventure

**Size**
* Ranging between 70 and 76 (MB)

**Android versions**
* 4.1-7.1.1

 ### I would suggest anyone developing a paid app for the Playstore to stick to these requirements.

**Category**
* Game          
* Education      
* Family         
* Photography    
* Weather

**Content Rating** 
* Mature 17+
* Everyone 10+ 

**Geners**
* Arcade;Action & Adventure    
* Card;Action & Adventure      
* Action                       
* Puzzle;Brain Games           
* Sports;Action & Adventure 

**Size**
* Ranging between 0 and 29 (MB)

**Android versions**
* 4.1 and up

**Price**
* 1 to 13 Dollers 

## Other Findngs 📰
* App with the smallest size earned the highest ratings
* The highly reviewed applications has received numerous downloads from users.
* The majority (64%) of apps in the Google Play store received generally positive reviews.

