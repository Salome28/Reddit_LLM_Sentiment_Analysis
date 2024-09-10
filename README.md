# Reddit Sentiment Analysis

Project by [Salomé NKB](https://linkedin.com/in/salome28) (@Salome28), [Marta Fonseca](https://linkedin.com/in/mcrfonseca) (@Martacrf), [Taylor Shook](https://linkedin.com/in/taylorshook) (@Taylorshook1).

### Exploration of sentiment trends and key discussion topics across multiple subreddits using Natural Language Processing, comparing data from 2019 to the present.

### **Key question: Are people angrier these days ?**
Determine the tendency of negative feelings among people in the world by analyzing the sentiment of comments on Reddit. We will compare comments from 2019 to those from the present across 40 subreddits. Our aim is to identify whether comments have become more negative or positive over time and uncover the key words frequently used in discussions.

### **Key areas of analysis:**
- Sentiment Trends: Analyze whether there is an observable trend in the sentiment of Reddit comments over time. Are comments becoming more negative or positive? </br>
- Topic Identification: Discover what people are talking about in various subreddits by identifying common themes and topics.</br>
- Frequent Words: Determine the most frequently occurring words in comments to understand the general sentiment and topics of discussion.</br>
- General Sentiment: Assess the overall sentiment distribution of comments to see if they are predominantly positive or negative.</br>

### Sentiments

For these particular analysis we wanted to focus on 7 emotions : 

- Joy
- Sadness
- Fear
- Disgust
- Neutral
- Anger
- Surprise

##### Data Source:
We are using two main data sources:
- [Dataset containing 1 million Reddit comments from 40 subreddits collected in 2019](https://www.kaggle.com/datasets/smagnan/1-million-reddit-comments-from-40-subreddits?resource=download) </br>
- Comments retrieved from the same 40 subreddits using the Reddit API, focusing on the most recent data available.
</br>

### Limitations :
- Kaggle dataset limited to May 2019
- Scraped data limited to within days of scrape time and power

  
### For future analysis, we recommend : 
- Adjusting the scraping technique to get comment data from other years.
- Taking a deeper look at the content of the comments.
- Creating a proper training set to fine-tune the model in order to predict other emotions.
- Focusing on a single subreddit to analyze trends within a smaller community.
