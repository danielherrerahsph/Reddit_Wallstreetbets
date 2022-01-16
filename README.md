# Reddit Wallstreetbets

**Problem Statement: 
The wallstreetbets reddit community gets a lot of flack for its incredibly bold -- at times, downright absurd -- trades. However, it was very right about the GME saga. How can I measure the success of the community in taking certain trade positions?** 

Well, I began with some initial analysis which can be seen in the 'stocks' file. This file includes a much more detailed outline of my thought process and steps. However, I will breifly summarize the key tools used: regular expressions, beautiful soup, praw, matplotlib, pandas. The current analysis is essentially EDA and walks through a hypothetical outcome if you had invested $100,000 on the top mentioned stocks of previous months compared to investing simply in $QQQ. *Spoiler*: buying said stocks did not seem to be effective when compared to buying the $QQQ ETF.

![Test Image 4](https://raw.githubusercontent.com/danielherrerahsph/Reddit_Wallstreetbets/main/wsb.png)

Note: My personal client information was hidden for the API. You will need to insert your own, specifically for the reddit API wrapper (praw). 

Python's webscraping capabilities, especially within reddit, make this a more logical choice for this task. The visualization and general data wrangling could have been conducted using either python or R, but to practice with python I chose to stay within python for these tasks. 

For additional analysis, such as text mining, I intend to switch over to R, which has the simplicity of many one-liner statistical analysis commands. 

Note: This project is ongoing. The next steps are to store the comment data for August to December of 2021. Then, using this comment data, create word clouds to visualize positive/negative sentiments and/or include profitability of such tickers over the subsequent month. Once data is collected, R will be used for sentiment analysis, using tidytext and other text mining packages. 

