## Binary-Class-Text-Classification-ML-NLP
By Tri Tran and Prudhvi Raju

## Goal: 
This documentation details the implementation of sentiment analysis on Twitter data through machine learning methodologies. Python, alongside prominent libraries like pandas, seaborn, nltk, and scikit-learn, is employed for the analysis. The dataset encompasses tweets labeled with sentiments, specifically classified as positive, negative, and neutral. 

The sentiment classification task in this context involves predicting one of the three sentiment labels for each tweet. To achieve this, we leverage two well-known machine learning algorithms: Random Forest and Logistic Regression. These algorithms are instrumental in handling the multiclass nature of the sentiment labels, aiding in the accurate categorization of tweets into positive, negative, or neutral sentiments. 

## Dataset: 
***
This data originally came from Crowdflower's Data for Everyone library.
As the original source says,
###
A sentiment analysis job about the problems of each major U.S. airline. Twitter data was scraped from February of 2015 and contributors were asked to first classify positive, negative, and neutral tweets, followed by categorizing negative reasons (such as "late flight" or "rude service").

The data we're providing on Kaggle is a slightly reformatted version of the original source. It includes both a CSV file and SQLite database. The code that does these transformations is available on [GitHub](https://github.com/benhamner/crowdflower-airline-twitter-sentiment)

For example, it contains whether the sentiment of the tweets in this set was positive, neutral, or negative for six US airlines: [Graph](https://www.kaggle.com/code/benhamner/exploring-airline-twitter-sentiment-data?scriptVersionId=0) 

## Data Processing (Tri)
## Model Prep (Prudhvi)

# Running instruction:
<br>git clone https://github.com/trantn1317/text-classification-ML-NLP.git<br>
<br>Check if Jupyter Notebook is installed.<br>
<br>If not, install it by using pip install jupyter-notebook<br>
<br>cd "into-the-repo-location" (make sure to replace this with your path to the cloned repo without quotes)<br>
<br>Once you are in jupyter environment, run the below file:<br>
<br>basic_model.ipynb<br>

## References: 
* Gresham, Richard. "Weak Supervision with Incremental Source." [Source](https://paperswithcode.com/paper/weak-supervision-with-incremental-source) 

* Hosseini, Sohail. "Twitter US Airline Sentiment Analysis." [Source](https://towardsdatascience.com/twitter-us-airline-sentiment-analysis-91caa7a22a93)https://towardsdatascience.com/twitter-us-airline-sentiment-analysis-91caa7a22a93 

* Rane, Ankita; Kumar, Anand. "Sentiment Analysis of Twitter Data." [Source](https://ieeexplore.ieee.org/document/8377739)https://ieeexplore.ieee.org/document/8377739 

 
