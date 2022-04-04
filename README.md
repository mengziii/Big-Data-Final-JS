# Big-Data-Final-JS
Jossa Soto jossa.soto@ryerson.ca  
Supervisor: Dr. Tamer Abdou

### Dataset
> Eight, F. (2019, October 16). Twitter US airline sentiment. Kaggle. Retrieved January 20, 2022, from https://www.kaggle.com/crowdflower/twitter-airline-sentiment

### Project description
Using Natural Language Processing (NLP) on the Twitter US airline sentiment dataset to classify and understand the sentiments from the text. It also identifies the more appropriate classifier between decision trees and Naive Bayes. 
> [Initial code](https://github.com/mengziii/Big-Data-Final-JS/blob/d90c5f522ec1b1b8896a059ade3ea83d9c62e9f8/Big%20Data%20Project%20R%20initial%20code-JS.Rmd) can be read with the three classifiers applied. 

> [Partial report](https://github.com/mengziii/Big-Data-Final-JS/blob/80cac814f043aae06446bdaaa94edc8f430b8cf4/CIND%20820%20Big%20Data%20Analytics%20Project%20-%20Jossa%20Soto.docx) can be downloaded

> [Report Presentation]

### Description of Data
The dataset contains 14,640 entries with 15 variables including the tweet text and class. The data is imbalanced with a large fraction of tweets classified as negative. Data is balanced by under sampling the negative and neutral sentiments. This results in 7,363 records in the subset that is used in the project.

### Methodology
The data is preprocessed where various elements such as punctuation, numbers, URLs, whitespaces are removed. Once the data is cleaned, is tokenized using three techniques: TF-IDF, Bag-of-Words, and Unigrams. Once the data is tokenized using the three different techniques, the algorithms decision tree, random forest, and Naive Bayes will be applied on the data. The data will be trained and tested through each algorithm then accuracy measures (sensitivity and specificity), efficiency, and stability will be assessed. 
