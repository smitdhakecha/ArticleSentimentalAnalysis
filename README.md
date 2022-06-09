# ArticleSentimentalAnalysis


### Python Dependencies Requirements

- Transformers
- BeautifulSoup
- Nltk
- Requests
- Re
- Matplotlib


### Execution

The code for webscraping of the articles and the sentimental Analysis is in the code.ipynb.

### Summary

I used the requests module to obtain the website information, from which I obtained the 10 most recent articles, for running the sentimental analysis algorithm. I cleaned the data I obtained from the website, and tokenized it to pass to the model. After getting the sentiments, I plotted the pie chart showing the polarity/sentiment of the articles. 

### The visualization of the Sentimental Analysis

On the 10 articles that have been scraped from the <a href="https://www.aljazeera.com/where/mozambique/"> website</a>, After running the sentimental Analysis, I found 7 articles to be of the Negative Sentiment, 1 to be of Neutral, and 2 of the positive sentiments. 

<img src=Result.png> </img>
