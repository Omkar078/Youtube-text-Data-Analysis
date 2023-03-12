# Youtube-Data-Analysis
In this study, YouTube data was used, and several analyses were conducted in accordance with problem descriptions. Data comprises of 0.6 million entries.

## Problem Statement:
### 1. Perform Sentiment analysis on every comments 
For this analysis textblob is used. Iextblob is a python library for processing texttual data. It provides simple API for dividing into common natural processing tasks. Using textblob sentiment is measured on the basis of polarity and subjectivity. Polarity is measured in the scale of -1 to 1. 
#### Outcomes:
- Comments with positive sentiments: 19390
- Comments with negative sentiments: 3508

### 2. Check most frequently used words in comment
Analysis is carried out using Wordcloud library. A word cloud (also called tag cloud or weighted list) is a visual representation of text data. Words are usually single words, and the importance of each is shown with font size or color. Python wordcloud library also perform same analysis.
#### Outcomes:
- Most frquent words used in Positive comments:

![image](https://user-images.githubusercontent.com/86731206/224532115-e2948a03-cf6b-46ec-a869-b29157028887.png)

- Most frequent words used in Negative comments:

![image](https://user-images.githubusercontent.com/86731206/224532210-18a6808e-50c4-4542-ad37-f61fe7763537.png)

### 3. Emoji analysis
To address this problem statement emoji library of python is used. The Python emoji module is a third-party library that allows developers to easily add emojis to their Python applications. It provides a range of functions and utilities to work with emojis, including emoji data and descriptions, as well as a function to convert text to emojis. First comments containing emojis has been extracted.
#### Outcomes:
- Total comments containing emojis: 65954
- Most frequent used emojis:

![newplot](https://user-images.githubusercontent.com/86731206/224532803-eb1ef85b-e8ba-4828-a4c2-89b8029546af.png)

