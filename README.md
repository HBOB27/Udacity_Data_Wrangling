# Introduction
Real-world data rarely comes clean. Using Python and its libraries, you will gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it. This is called data wrangling. You will document your wrangling efforts in a Jupyter Notebook, plus showcase them through analyses and visualizations using Python (and its libraries) and/or SQL.

The dataset that you will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. 

# Goal: 
wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations. The Twitter archive is great, but it only contains very basic tweet information. Additional gathering, then assessing and cleaning is required for "Wow!"-worthy analyses and visualizations.

# Gathering:
The twitter-archive-enhanced.csv file was given by Udacity which contains most of the data needed for each tweet (tweet ID, timestamp, text, name, rating,etc...). The second data was the image prediction file that was given as a link and should be downloaded porgramatically using python and pandas. This file contains prediction results of three different algorithms that predict the image of the tweet with % of confidence and the breed of the dog. Third data was collected through the Twitter API after creating a developer account on twitter. This data Contained the number of retweets and favorites for each tweet. 

# Assessing:
Categorize the issues under quality and tidiness. Some of the issues were detected through Visual assessment like name of the columns in the prediction table, and prediction dog names were of lower and upper case. But for sure not all the issues can be detected by the eye, so you need Programmatic assessment that can detect several issueslike wrong datatypes and many null values. 

# Cleaning:
Clean the data quality and tidiniss issue so that your data would be ready for analyzing!
