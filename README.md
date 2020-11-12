![youtube](https://user-images.githubusercontent.com/70446836/98875791-ed290380-244a-11eb-9883-2486d9b81acc.png)


# Youtube Trends
Team Members: Desiree Herschberger, William Pappas, Thomas Keane, Tas Nahar, Redeat Bekele, Sveena Sharma

## Motivation 
  YouTube is a gigantic video-sharing platform based in San Bruno, California that earned a revenue of $15 billion in 2019. Due to the vast number of published videos, it is difficult to understand which categories, channels, or videos themselves are the most popular over time. It would seem reasonable that stakeholders in YouTube would like to understand what is trending and how their users interact with these videos. Is there a connection between the number of views, likes, dislikes, and comments on a given video? Is there a reason that certain video categories perform signifcantly better than other categories? Is it possible to predict user behavior over time? If these factors are known, it would be benefical for not only the executives/stakeholders, but the creators themselves to be able to predict success or failure.
  
  This repository consists of analysis performed on various YouTube datasets and includes observable trends. The data includes the Top US Trending Videos from Kaggle for August to November of 2020. It also includes three datasets from YouTube API: YouTube Search Items, YouTube Video Statistics, and Youtube Channel Statistics. This repository includes trend analysis on user behavior, video statistics, channel statistics, and category statisics from 2019 and 2020. It also provides insights during the strict Covid Lockdown in the US from March to June 2020.  

  HYPOTHESES: 

  - Societal events will align with YouTube Trends (ex. quarantine challenges/vlogs, new music video releases, video games etc.) 
  - If viewer count increases, viewer reactions will increase as well. This includes number of likes and dislikes as well as number of comments. 
  - Compared to 2019, YouTube viewing will increase in 2020 due to the pandemic. 
  - The lockdown will not affect the viewer trends because trends will remain consistant regardless social circumstances. 

Please review the following links to review the final data analysis and data exploration/clean-up process:

  Jupyter Notebook  - Final Data Analysis

  Jupyter Notebook - Data exploration and cleanup process
  
## Table of Contents

## Questions Addressed
1) Why were certain categories trending during specific times?
2) Is there a relationship between certain user behaviors: View Count, # of Likes, # Dislikes, # Comments
3) Is there a difference in viewing habits from 2019 to 2020? Did the strict COVID lockdown in early 2020 impact viewer trends?

## Data Sources
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

## Data Cleaning and Exploration
Describe the exploration and cleanup process
Discuss insights you had while exploring the data that you didn't anticipate
Discuss any problems that arose after exploring the data, and how you resolved them
Present and discuss interesting figures developed during exploration, ideally with the help of Jupyter Notebook

## Data Analysis 
## Summary Statistics 

- Top five liked videos from August to November 2020

- Most published videos per category 

- Least published videos per category

- Top Trending Channels from August to October 2020

- Relationship between view count and reactions per category 

- Compare the top two categories: Music vs. Entertainment: 

- Most watched videos in 2019 vs. Most watched videos in 2020

- The most viewed quarantine challenge videos during strict COVID lockdown 

## Findings and Observations 

## Post - Mortem 
Difficulties: 

- Due to the large datasets, with both the CSV and YouTube API, it was difficult to create a narrative for this project. The team had to figure out what data we wanted to pull and how we could connect the CSV and YouTube API datasets to form a bigger picture. We had a few meetings to discuss the overall importance and what the ultimate purpose was with our findings. All in all, it took time to figure out why we wanted this data and how it could prove useful for the YouTube community, whether that be investors or creators themselves. 
- Another difficulty involved reading the API and performing the API calls itself. It was a challenge to repeatedly call the API without going over the quota. There are only so many requests we could do and we had to implement another method that allowed us to continue our analysis without overextending our API limit. 
- Finding a commonality between the data frames in order to merge them effectively was another challenge. Some video IDs and channel IDs were actually dropped during the merge due to duplicates and irrelevancy. ASK REDEAT ABOUT THIS!!! 
- Lastly, it was difficult to set the appropriate axes' values for our charts. For a few charts, Billy and Desiree had to manually input the limits in order to maintain consistancy and display the correct values. 

Future Possibilities: 

If we had two more weeks to work on this project, we would have conducted the following analysis:
- Revenue: At what point do channels earn the most money? Is it based off societal circumstances or the content itself that was published? How does one youtube creator earn more money compared on another popular creator? What are the factors that contribute to these earnings (view count, subscriber count, ad-sense, etc.)
- We are also interested in learning how to export large datasets from the csv in order to compare daily statistics between 2019 and 2020, but we are not sure how to export such large datasets. 
- It would  be interested to predict subscriber count for trending channels. Is it possible forecast this number with the provided datasets?

