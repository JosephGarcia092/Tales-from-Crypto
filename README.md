# Tales-from-Crypto

## Sentiment Analysis 
------
In the Sentiment Analysis I used my current knowlege of using APIs to get info on not only _stock Data_ but also _newsapi_ to get the current news on what
Ethereum and Bitcoin.
- Setting up enviroments for my APIs to get all the recent news articles about Both Currencies.
- Setting up my for loops to analyze each article for a Sentiment Analysis.
- Analyzing the Two Currencies Sentiment Analysis
  - _Highest Mean Positive Score_
  - _Highest Negative Score_
  - _Highest Positive Score_
  
  
### NLP and WordCloud 
-------

* Set up my function to Take in the articles from the previous section to _Tokenize_ text in the articles. 
* Used my knowledge of Python and Pandas to find stop words and to create new stop words to filer out words that are not meaningful in the project.
* Created #DataFrame to put all the articles and the newly created tokens to vizualize for User
* Took in the Newly Created DataFrame to count the instances of of the Tokenized words over all the articles. 
* Created a wordcloud to show how the words that are being used commonly. 

#### NER
---

- Using the Knowledge of Spacy to bring in all the articles to render the Visualization of Entities over all the articles. 
- Displaying all the Entitiies that are repeatedly showing up in the articles for each Currency. 
