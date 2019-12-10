# Predicting Reddit depression posts using Reddit API

The world witnesses one suicide incident every 40 seconds with an average total of 800,000 incidents each year. This number has higher than the number of people dying in wars, Malaria, breast cancer and homicide. The World Health Organization released new data that is alarming. There is 139% increase of suicide rate in women in the U.S. between 1999 and 2017. the rate for men increased by 79% for that same period.

### Introduction
In the project, i am analyzing two subreddits from the Reddit API; r/Offmychest and r/Depression. These Two subreddits are very similar to each other. The first has posts from users who are just sad, example: complaining about their day, traffic, life... Depression subreddit users usually talk more about hurting themselves or their need to, sadly, end their life. I am collecting 50,000 posts from each subreddit and trying to find a model that can beat the baseline model of 50%.

### Objective
Its important to find people who are suffering from depression and help them get the essential medical help they need before they get worse. Using Reddit API and different modeling techniques to distinguish between depressed and sadness might help us generalize our model to websites and platforms other than reddit.

### Visualization
Here, we can visualize the word count for each of the sub reddits:

Offmychest             |  Depressed
:-------------------------:|:-------------------------:
![](https://github.com/AlaaSenjab/classifying_reddit_topic/blob/master/img/offmy_word_freq.png)  |  ![](https://github.com/AlaaSenjab/classifying_reddit_topic/blob/master/img/dep_word_freq.png)

### Conclusion:
In this project, i used multiple estimators and transformers to find which one gives the best results. Overall, Most of the models were overfitted. Adjusting the hyperparameters will help balance the model, but the data is big and requires a lot of time to find that balance.

Regardless, Logistic Regression was the best, it gave 81% accuracy score. Even though this score is low, the subreddits i choose were very similar in content and the use of words. The baseline model is 50%, so we bet it by 30%. Thats great!

Even though this model can be improved, we can use this model to find users who are depressed on platforms other than reddit. Finding these people and offering them help is very important.