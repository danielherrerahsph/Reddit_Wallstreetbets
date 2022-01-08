# Reddit Wallstreetbets

**Problem Statement: 
The wallstreetbets reddit community gets a lot of flack for its incredibly bold -- at times, downright absurd -- trades. However, it was very right about the GME saga. How can I measure the success of the community in taking certain trade positions?** 

Well, I began with some initial analysis which can be seen in the 'wsb_initial' file. This file includes a much more detailed outline of my thought process and steps. However, I will breifly summarize the key tools used: regular expressions, beautiful soup, praw and pandas. You can currently take a look at the returns (%) you would have made if you followed the most mentioned stocks on the daily discussions for November 2020. *Spoiler*: buying said stocks did not seem to be effective when compared to buying the QQQ ETF.

Note: My personal client information was hidden for the API. You will need to insert your own, specifically for the reddit API wrapper (praw). 

Python's webscraping capabilities, especially within reddit, make this a more logical choice for this task. For additional analysis, such as regression modeling, I intend to switch over to R, which has the simplicity of many one-liner statistical analysis commands. 

Note: This project is ongoing. The next steps are to store the comment data for August to December of 2021. Then, using this comment data, create word clouds to visualize positive/negative sentiments and/or include profitability of such tickers over the subsequent month. Once data is collected, R will be used for sentiment analysis, using tidytext and other text mining packages. 

