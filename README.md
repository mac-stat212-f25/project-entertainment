# TikTok Video Popularity Analysis : What Makes TikTok Videos Go Viral? 

## Project Overview

This repository contains the code, data processing scripts, and visualizations for our project **“TikTok Video Popularity Analysis: What Makes TikTok Videos Go Viral?”**

Our project investigates how users engage with TikTok content, examining both **entertainment videos** and **informational/news-like videos**. We analyze trending TikTok video metadata and engagement metrics to understand:

- Which video characteristics (hashtags, music, video length, followers, etc.) best predict virality  
- How engagement patterns differ between *entertainment* vs. *news/informational* content  
- How posting time, language, and topic influence average engagement rate  
- What these patterns reveal about how people consume news on TikTok

## Software Requirements

1. **Which factors most strongly predict TikTok video popularity?**  
2. **How does engagement differ between entertainment and news-style TikTok content?**  
3. **What patterns in TikTok video trends help explain how users consume information on social media?**

## How to Run the Project

TikTok has become one of the most influential platforms for both **entertainment** and **information sharing**.  
Younger users primarily consume entertainment content, while an increasing number of adults rely on TikTok for *news and current events*.  

By comparing how different types of videos perform, we aim to understand how TikTok shapes the way different generations learn, interact with, and share information.

## Repository Structure

- **Source:** Kaggle  
- **Link:** https://www.kaggle.com/datasets/erikvdven/tiktok-trending-december-2020  
- **Format:** CSV + JSON  
- **Size:** ~1000 trending videos  

## Expected Output

- Followers count (`authorMeta.followers`)
- Video length (`videoMeta.duration`)
- Video caption (`text`)
- Hashtags (`hashtags`)
- Music used (`musicMeta.musicName`)
- Likes (`diggCount`)
- Shares (`shareCount`)
- Views (`playCount`)
- Comments (`commentCount`)

## Software Requirements

To run this project, install:

- **R ≥ 4.4.0**
- **RStudio ≥ 2024.12**
- **Quarto ≥ 1.4** (for rendering `index.qmd`)

### **Required R packages**
```r
install.packages(c(
  "tidyverse", "dplyr", "ggplot2", "viridis", "lubridate",
  "stringr", "readr", "jsonlite", "forcats"
))
