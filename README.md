## 🇮🇳 YouTube India Trending Video EDA(2017 - 2018)

YouTube is the most popular and most used video platfrom in the world today. YouTube has a list of trending videos that is updated constantly. Here we will use Python with some packages like Pandas and Matplotlib to analyze a dataset that was collected over 205 days. For each of those days, the dataset contains data about the trending videos of that day. It contains data about more than 37,000 trending videos. We will analyze this data to get insights into YouTube trending videos, to see what is common between these videos. Those insights might also be used by people who want to increase popularity of their videos on YouTube.

The dataset that we will use is obtained from Kaggle. It contains data about trending videos for many countries. Here we will analyze trending videos in India.

A focused exploratory data analysis of YouTube’s trending videos in India, uncovering patterns in viewership, engagement, publishing behavior, and content characteristics—no machine learning models included.

---

## 🔎 Project Objectives

- **Clean & Inspect** the dataset: merge category info, handle missing values  
- **Describe** numerical and categorical variables  
- **Visualize** distributions of views, likes, comments  
- **Analyze** text features: capitalized words, title lengths  
- **Explore** correlations between metrics  
- **Identify** top channels and categories by trending count  
- **Investigate** publishing patterns (day of week, hour)  
- **Flag** quality issues: errors, disabled comments/ratings

---

## Goals of the Analysis

We want to answer questions like:

- How many views do our trending videos have? Do most of them have a large number of views? Is having a large number of views required for a video to become trending?
- The same questions above, but applied to likes and comment count instead of views.
- Which video remained the most on the trendin-videos list?
- How many trending videos contain a fully-capitalized word in their titles?
- What are the lengths of trending video titles? Is this length related to the video becoming trendy?
- How are views, likes, dislikes, comment count, title length, and other attributes correlate with (relate to) each other? How are they connected?
- What are the most common words in trending video titles?
- Which YouTube channels have the largest number of trending videos?
- Which video category (e.g. Entertainment, Gaming, Comedy, etc.) has the largest number of trending videos?
- When were trending videos published? On which days of the week? at which times of the day?

---

## 📊 Key Findings

 - Views & Engagement distributions are heavily skewed: a few videos rack up most views.
 - Title features (length, capitalization) show mild correlation with engagement.
 - Top channels and categories dominate trending lists (Music, Entertainment).
 - Publishing times cluster around evenings and weekends.
 - A small fraction of videos have errors or disabled comments/ratings.

---

## Libraries Used

- Pandas 
- Numpy 
- Matplotlib 
- Seaborn 
- Wordcloud
- plt.rcParams
- json

   

