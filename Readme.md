Overview:

In this project, I performed an analysis of customer reviews for BOAT headphones on Amazon. I used Jupyter Notebook with Python, Pandas, Regex, and Wordcloud to analyze the data. In addition, I used the OpenAI API to generate positive and negative tags from the customer reviews.

Data:

The data for this analysis was obtained from Amazon's website. I scraped the customer reviews for BOAT headphones and stored them in a CSV file. The data consisted of the customer's review text, the star rating they gave the product, and the date they posted the review.

Analysis:

Data Cleaning
Before analyzing the data, I had to clean it. I removed any rows with missing data. I used Regex to remove any non-English characters like \n and STOPWORDS also using wordcloud library.

Sentiment Analysis:

To perform sentiment analysis, I used the OpenAI API. I generated positive and negative tags for each review, which helped me to better understand the sentiment of each review.

Wordcloud:

I used Wordcloud to visualize the most common words in the customer reviews. The larger the word, the more times it appeared in the reviews.

Insights:

![Wordcloud - Positive Resposes](https://github.com/Analyst-Ninja/Amazon-BOAT-Headphones-Review-Analysis/assets/81576967/12607ef6-6fc2-4326-9480-9d307a7e1fca)

Features that are appreciated by the customers are given below:
1.	Sound Quality 
2.	Good Battery Life
3.	Good Service
4.	Build Quality
5.	Noise Cancellation

![Wordcloud - Negetive Respose](https://github.com/Analyst-Ninja/Amazon-BOAT-Headphones-Review-Analysis/assets/81576967/e230a982-d7fc-4197-95e0-47d468a118aa)

Points given below product needs to work on to win customers:
1.	Noise Cancellation
2.	Battery Issue
3.	Voice Quality
4.	Connectivity Issue
5.	Charging Issue

Conclusion: 

In conclusion, my analysis showed that the BOAT headphones were generally well-liked by customers. By using the OpenAI API to generate positive and negative tags, I was able to gain deeper insights into the sentiment of the reviews. The word cloud provided a visual representation of the most common words used in the reviews.
