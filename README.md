# Ryerson University Data Analytics Final Project by Kyuhwan Kim
 By: Kyuhwan Kim kyuhwan.kim@ryerson.ca
 <br />
 Supervisor: Dr. Tamer Abdou tamer.abdou@ryerson.ca   
 <br />
 The website for the program: <br />
 https://continuing.ryerson.ca/public/category/courseCategoryCertificateProfile.do?method=load&certificateId=171618
 <br /><br />
 The dataset used for this project: <br />
 >Sun, J. (2016, August). Daily News for Stock Market Prediction, Version 1. Retrieved [Date You Retrieved This Data] from https://www.kaggle.com/aaron7sun/stocknews.
<br />

Description of Project:

Using NLP (Natural Language Processing), a model is developed using news articles to predict the movement of the stock market. Also experimented with historical stock data to predict future movement(time series)

Open [Data_Analytics_Final_Project_for_Kyuhwan_Kim.ipynb](https://github.com/QOneK/Ryerson-Data-Analytics-Final-Project-for-Kyuhwan-Kim/blob/master/Data_Analytics_Final_Project_for_Kyuhwan_Kim.ipynb)
to view the code for the project. 

You can also see the [report](https://github.com/QOneK/Ryerson-Data-Analytics-Final-Project-for-Kyuhwan-Kim/blob/master/Final%20Project%20for%20Kyuhwan%20Kim.docx?raw=true) and [presentation slides](https://github.com/QOneK/Ryerson-Data-Analytics-Final-Project-for-Kyuhwan-Kim/blob/master/Prediction%20of%20Stock%20Market%20Using%20NLP%20(Natural%20Language%20Processing).pptx?raw=true)

Dataset contains these files:
 1. **RedditNews.csv:** 
    Date | News
    ------------ | -------------
 
    Historical news headlines from Reddit WorldNews Channel (/r/worldnews). They are ranked by reddit users' votes, and only the top 25 headlines are considered for a single   date. (Range: 2008-06-08 to 2016-07-01)
 
 2. **DJIA_table.csv:**
     Date | Open | High | Low | Close | Volume | Adjusted Close 
     ------------ | -------------| -------------| -------------| -------------| -------------| -------------

    Downloaded directly from Yahoo Finance. DJIA = Dow Jones Industrial Average

3. **CombinedNewsDJIA.csv:**
    Date | Label | Top1 -> Top25 Newsheadlines 
    ------------ | -------------| -------------
    
    The RedditNews and DJIA data were combined. The class label is labelled as '0' when DJIA falls and '1' if matained/increased. 


 These dataset files can be found at the [Database](https://github.com/QOneK/Ryerson-Data-Analytics-Final-Project-for-Kyuhwan-Kim/tree/master/Dataset) folder




