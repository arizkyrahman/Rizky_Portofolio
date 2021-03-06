# [Project 1: Data Science Salary Estimator](https://github.com/arizkyrahman/ds_salary_project)
- Created a tool that estimates data science salaries (MAE ~ $ 11K) to help data scientists negotiate their income when they get a job.
- Scraped over 1000 job descriptions from glassdoor using python and selenium
- Engineered features from the text of each job description to quantify the value companies put on python, excel, aws, and spark.
- Optimized Linear, Lasso, and Random Forest Regressors using GridsearchCV to reach the best model.
- Built a client facing API using flask

![](/images/positions_by_state.png)

# [Project 2: Ball Image Classifier](https://github.com/arizkyrahman/ball-image-classifier)
I built a ball classifier to identify balls from different sports. This could be useful for someone who is new to sports from a certain country. They could take a picture of a ball and an app could serve them some information about the history and rules of the game. This is the underlying model for building something with those capabilities. 

I was able to get the model to predict the sport of the ball with 94% accuracy after minimal tuning. For most of the cases this would meet the need of an end user of the app. To get these results I used transfer learning on a CNN trained on resnet34. This created time efficiencies and solid results.

![](images/matrix_results.png)

# [Project 3: Twitter Sentiment Analysis](https://github.com/arizkyrahman/Twitter-Sentiment-Analysis)
- Deal with the tweets database that are avaialble to us by the Twitter. 
- Clean the tweets and break them out into tokens. 
- Analysis each word using Word Cloud concept.
- Rate each word on the basis of the score wheter it is positive, negative and neutral.

![](images/twitter_sentiment_analysis.png)
