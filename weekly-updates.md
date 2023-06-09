***Week 2***

**What did you do last week?**
* Created project proposal and posted to class for feedback
* Set up website on github
* Researched market analysis domain, what kind of insights businesses might look for in a market analyzer tool, the data those insights might come from, and where to find that data
* Preemptively decided on a plan going forward, that this tool will conduct sentiment analysis on Twitter post data to find market gaps where needs are not being fulfilled by current products or services, organized by industry, with the goal of being able to identify potential profitable areas for entrepreneurs to find new market niches in. 

**What do you plan to do this week?**
* Find out how to access Twitter data and understand how its API works for subsequent analysis

**Are there any impediments in your way?**
* I'm not very familiar with APIs.
* Twitter data may not be as useful to me as I hope
* I do not know exactly where to start looking and how to get the data I need. 

**Reflection on the process you used last week, how can you make the process work better?**
* Last week I was in brainstorming mode, without very specific plans. This week, I would like to start making concrete actionable plans for exactly what needs to happen for this project. I think this should happen naturally as I dive into more specific problems and have to come up with solutions. 

***Week 3***

**What did you do last week?**
* Became more familiar with Github and posted my first weekly update both on my website (here) and on Piazza
* Read through the Twitter course for how to understand and use their API: https://github.com/twitterdev/getting-started-with-the-twitter-api-v2-for-academic-research/blob/main/README.md
* Created a Developer account on Twitter, and created my first project and app, titled MLMarketAnalyzer

**What do you plan to do this week?**

* Practice using the API by pulling some sample data on Python
* After getting confident using the API, research and decide which data I will pull and use for my analysis, and then extract it so that it is ready for analysis

**Are there any impediments in your way?**

* I have never used an API before, so there will probably be some hiccups in the process of using it and getting the data on Python
* I'm still a little vague on exactly which data I need/want to use for my analysis, so I need to think about this and decide what kind of tweets I want to look at for analysis
* I will have to figure out a way to store my data in a way that both makes sense for my project and so that I keep my data in compliance with Twitter policies - in other words I will have to find a way to honor Tweet deletions or changes

**Reflection on the process you used last week, how can you make the process work better?**

* I was glad to find a way to easily familiarize myself with the Twitter API, and reading through this was no problem. Familiarizing myself with Github was harder than I anticipated, and I will keep this in mind as I continue to use this website for my project. Again, I'm still vague on a lot of points about my project, and this might be because I'm hoping I'll learn more information as I go along with my classes and with the project that will help push me one way or another in terms of decision-making, but what I really need to do is simply do my own research and figure out actionable strategies to move forward decisively. A good plan today is better than a perfect plan tomorrow, and I need to keep reminding myself of that.


***Week 4***

This week, I focused on trying to query and acquire the data from the Twitter API. This has proven to be much more confusing and frustrating than I anticipated unfortunately - this is my first time dealing with these API's, and there are several differing sources of information online as to how to access and use the Twitter data, adding to my general confusion. I may have to spend a little extra time this weekend contacting Developer Support if I still cannot get a handle on this problem. I managed to set up some code in a Jupyter notebook and install a lot of different packages and libraries, and I spent quite a bit of time looking through the provided github on how to use the API, but I still had trouble getting any data to work with. I wanted to get this accomplished this week, and unfortunately I didn't meet that objective, so I will put in some extra time to ensure this is accomplished, so I can work on exploring the data next week and doing preliminary analysis. 

***Week 5***
This week unfortunately was unproductive, and I did not post a timely update or make any progress. 

***Week 6***
This week, I was able to make a lot of progress. Firstly, I was able to figure out how to use the Twitter API via the twitter library on Python, and went through and tested how to use the search functions to find tweets, user information, etc. I then spent a great deal of time installing various libraries and brainstorming my process for how I would proceed with finding market gaps and conducting sentiment analysis. After successfully conducting sentiment analysis on some sample data, I went about deciding exactly which tweets I would need to gather for a robust analysis. I have envisioned creating a tool for potential entrepreneurs that don't really know where to start looking for business ideas, so I decided to gather random tweets from populous areas in the United States and attempt to extract information that could lead to market gap analysis. After trying a couple different models, and not finding any strong data that could be used for analysis (surprisingly enough, most people who are tweeting aren't revealing market gap information with their random tweets), I decided to rethink my goals and subsequent approach. Now, what I'd simply like to do is create a NLP model with machine learning techniques that can match a given tweet to a specific industry- someone could then use this model to find tweets about certain industries and conduct robust sentiment analysis on these tweets, but I believe creating this model is a necessary first step for the tool that I was originally envisioning, and a better way for me to ustilize the machine learning techniques I've been learning in this progaram. My plan going forward is to manually create a list of hashtags that I can use to find tweets by industry, and then generate the dataset I need with manual labeling - then I can use NLP or other properties of the tweets to create a model that can categorize a tweet nto a specific industry. In short, I have my plan all set, and I just need to work out the details, such as specific functions, compliance techniques for data gathering/storage, and other kinks. I'm feeling much more confident than I was last week. 
