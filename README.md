# NewsMood

In this assignment, you'll create a Python script to perform a sentiment analysis of the Twitter activity of various news outlets, and to present your findings visually.

Your final output should provide a visualized summary of the sentiments expressed in Tweets sent out by the following news organizations: BBC, CBS, CNN, Fox, and New York times.

The first plot will be and/or feature the following:


Be a scatter plot of sentiments of the last 100 tweets sent out by each news organization, ranging from -1.0 to 1.0, where a score of 0 expresses a neutral sentiment, -1 the most negative sentiment possible, and +1 the most positive sentiment possible.

Each plot point will reflect the compound sentiment of a tweet.

Sort each plot point by its relative timestamp.


The second plot will be a bar plot visualizing the overall sentiments of the last 100 tweets from each organization. For this plot, you will again aggregate the compound sentiments analyzed by VADER.

The tools of the trade you will need for your task as a data analyst include the following: tweepy, pandas, matplotlib, and VADER.

Your final Jupyter notebook must:


Pull last 100 tweets from each outlet.

Perform a sentiment analysis with the compound, positive, neutral, and negative scoring for each tweet.

Pull into a DataFrame the tweet's source account, its text, its date, and its compound, positive, neutral, and negative sentiment scores.

Export the data in the DataFrame into a CSV file.

Save PNG images for each plot.


As final considerations:


You must complete your analysis using a Jupyter notebook.

You must use the Matplotlib or Pandas plotting libraries.

Include a written description of three observable trends based on the data.

Include proper labeling of your plots, including plot titles (with date of analysis) and axes labels.

Three Observable Trends
1) CNN was the only news source that had a negative sentiment
2) Fox was the most positive out of the media sources
3) NYTimes was closest to neutral for the overall media sentiment
