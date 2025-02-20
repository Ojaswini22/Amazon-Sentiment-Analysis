### Amazon gives a platform to small businesses and companies with modest resources to grow larger. And Because of its popularity, people actually spend time and write detailed reviews, about the brand and the product. So, by analyzing that data we can tell companies a lot about their products and also the ways to enhance the quality of the product.


Natural Language Processing (NLP) to overcome the problem of large datasets and analyze it. The task is to predict whether the review given is positive or negative.

Steps to be followed :

 1.Importing Libraries and Datasets
 
 2.Preprocessing and cleaning the reviews
 
 3.Analysis of the Dataset
 
 4.Converting text into Vectors
 
 5.Evaluation and Prediction
 
 Importing Libraries and Datasets
 
The libraries used are : 

Pandas : For importing the dataset.

Warning : To ignore all the warnings

Matplotlib : To plot the visualization. Also used Wordcloud for that.

To predict the Sentiment as positive(numerical value = 1) or negative(numerical value = 0), we need to change them the values to those categories. For that the condition will be like if the sentiment value is less than or equal to 3, then it is negative(0) else positive(1). For better understanding, refer the code.

