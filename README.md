# Youtube-text-Data-Analysis
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

### 4. Collecting entire data from Youtube
As per the problem statement there is need tto create a dataframe which contains entire data (which contains merging of data from individual CSV files). A Pandas library has been used to address this statement.
#### Outcomes:
Total Data after merging: 
- Rows: 375942
- Columns: 7

### 5. Which video categorry has maximum like
To addressing this problem the csv file is used which contains each and every category of the videos. Then  this CSV file is merge with original data frame.
#### Outcomes:
![image](https://user-images.githubusercontent.com/86731206/224534284-f3524788-a3d6-468d-b142-1fa12445209f.png)

### 6. Find out whether audience is engaged or not
In this problem statement analysis has been done to find relation between likes, dislikes and views of the audience.
#### Outcomes:
- Analysis between views and likes:

![image](https://user-images.githubusercontent.com/86731206/224534973-26ea54c2-763f-4efd-b53e-ab29be084854.png)
- Co-relation betweeen views, likes and dislikes:

![image](https://user-images.githubusercontent.com/86731206/224535019-713f9248-2b26-47a9-8650-f6867783e8dc.png)

### 6. Which Channels have the largest number of trending videos
Answer is there behind the problem statement, channel with the largest number of trending videos needs to be find out.
#### Outcomes:

![newplot (1)](https://user-images.githubusercontent.com/86731206/224535237-e7269d3a-bb93-424c-b9c9-44582564e5cb.png)

### 7. Find out relation between puctuations in tittle and tags have any relation with views, likes, dislikes and comments
In this problem statement most frequent used punctuations and relation between this punctuations with views, likes, dislikes and comments needs to be find out
#### Outcomes:
![image](https://user-images.githubusercontent.com/86731206/224535457-e3ec2677-2deb-4aff-8e8c-d2b6c89a594b.png)


