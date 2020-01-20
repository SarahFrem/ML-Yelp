# Data science project about Yelp dataset 

files provided : html version of the jupyter lab 

Research key question :  to what extent Yelp is a powerful indicator ? A study case in Arizona

Content summary : 
- Study of the differences of number of reviews versus given stars per locations and types of businesses. 
- Identification of a specific study case where this ratio shows pre-patterns regarding key question. 
- Merge with the reviews provided by Yelp
- Study all the new features toward the main open/close target and create new meaningful features on a spatial and time basis
- Study the review contents and any potential misclassification 
- Predicting the open/close binary. How well Yelp information can lead to a prediction of a closing restaurant? 

Methods used thoughout the study: 
  - Efficiently gathering Yelp keywords into meaningfull business categories : 
      * Google pre trained model of Word2Vect 
      * Clustering kmeans on cosine similiarities 
  - Using the standard and robust metics to evaluate the randomness of up-rated and down-rated restaurants 
  - Extracting insights from a spatial and temporal breakdown : 
      * Maps and Haversines distances 
      * Analysing frequencies of the rating 
  - Analysing reviews 
      * WordCloud per star 
      * Sentiment analysis through emoticons and Polarity values 
 - Identifying any grade missclassification 
      * Tf-idf matrix on reviews versus This matrix with binary emoticon sentiment 
      * Multinomial Naive Bayes versus Support Vector MAchine with a linear Kenerl
 - Studying the Yelp impact on the open or close business 
      * Tsne visualization 
      * Correctly checking correlation between continuous and discrete variables 
      * Logistic Regression and Random Forest


