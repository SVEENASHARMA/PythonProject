![youtube](https://user-images.githubusercontent.com/70446836/98875791-ed290380-244a-11eb-9883-2486d9b81acc.png)


# Youtube Trends
Team Members: Desiree Herschberger, William Pappas, Thomas Keane, Tas Nahar, Redeat Bekele, Sveena Sharma

## Motivation 
  YouTube is a gigantic video-sharing platform based in San Bruno, California that earned a revenue of $15 billion in 2019. Due to the vast number of published videos, it is difficult to understand which categories, channels, or videos themselves are the most popular over time. It would seem reasonable that stakeholders in YouTube would like to understand what is trending and how their users interact with these videos. Is there a connection between the number of views, likes, dislikes, and comments on a given video? Is there a reason that certain video categories perform signifcantly better than other categories? Is it possible to predict user behavior over time? If these factors are known, it would be benefical for not only the executives/stakeholders, but the creators themselves to be able to predict success or failure.
  
  HYPOTHESIS: 

  Social events will align with YouTube Trends - quarantine challenges/vlogs, music video releases, new video games etc. 
  If viewer count increases, reaction will increase as well. 
  We believe youtube viewing will increase in 2020 due to the pandemic compared to 2019.
  The lockdown will not affect the viewer trends because categories remain consistant regardless of social circumstances. 

  This repository consists of analysis performed on various YouTube datasets and includes observable trends. The data includes the Top US Trending Videos from Kaggle for August to November of 2020. It also includes three datasets from YouTube API: YouTube Search Items, YouTube Video Statistics, and Youtube Channel Statistics. This repository includes trend analysis on user behavior, video statistics, channel statistics, and category statisics from 2019 and 2020. It also provides insights during the strict Covid Lockdown in the US from March to June 2020.  

Please review the following links to see the project results:

  Jupyter Notebook  - Final Data Analysis

  Powerpoint Presentation 

  Jupyter Notebook - Data exploration and cleanup process
  
## Table of Contents

# Questions Addressed
1) Why were certain categories trending during specific times?
2) Is there a relationship between certain user behaviors: View Count, # of Likes, # Dislikes, # Comments
3) Is there a difference in viewing habits from 2019 to 2020? Did the strict COVID lockdown in early 2020 impact viewer trends?

# Data Sources
This project used a CSV file and YouTube API to create the datasets regarding trends overtime and in specific categories. The CSV file soley focuses on US Trending data whereas the YouTube API expanded internationally. The data collected was transformed in order to analyze and visualize with Python; it included the following factors: 

- Video Title
- Channel Title
- Publish Time
- Tags
- Views 
- Likes and Dislikes
- Description 
- Comment Count 

The youtube API consists of three datasets: YouTube API: YouTube Search Items, YouTube Video Statistics, and Youtube Channel Statistics. All three datasets are linked by the unique Video ID and Channel ID fields.

# Data Cleaning and Exploration
Describe the exploration and cleanup process
Discuss insights you had while exploring the data that you didn't anticipate
Discuss any problems that arose after exploring the data, and how you resolved them
Present and discuss interesting figures developed during exploration, ideally with the help of Jupyter Notebook

# Data Analysis 
## Summary Statistics 

# Findings and Observations 

# Post - Mortem 
Discuss any difficulties that arose, and how you dealt with them
Discuss any additional questions that came up, but which you didn't have time to answer: What would you research next, if you had two more weeks?


- Creating a narrative throughout the datasets: Working with such a big dataset in the CSV - difficulty created a project. what did we want to find and pull? how can we connect the csv and youtube api datasets?
- reading the api was difficult - trying to figure out to call the api without going over the quota limit? too many requests was possible 
- merging dataframes - finding a commonality 
- some video ids and channel ids were dropped during the merge 
- Billy and Des- difficulty creating the appropriate values on the axes on the charts. Billy / Des had to manually input axes limits in order for the charts to be consistent and display the correct values 

if two more weeks: add revenue - when do channels make the most money. is it based off social circumstance or the content published? how does one youtube creator earn more money compared on another? 


