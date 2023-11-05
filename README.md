# Flight Delays Prediction
All commercial flights that departed the Washington, D.C., region and arrived in New York in January 2004 are listed in the FlightDelays.csv file.  Whether a flight is delayed is the variable that we are attempting to predict. An arrival that is at least 15 minutes later than expected is considered a delay. 


## Data Preprocessing 

* Data Reduction: I Reduced the number of predictors using the necessary operation (domain knowledge, correlation matrix, etc.) and stored the result of this step in a new file “FlightDelaysTrainingData.csv” 
* Data Exploration stage: I made a copy to the “FlightDelaysTrainingData.csv” file and renamed it to “FlightDelaysDataExploration.csv” and use it to provide data summarization using four different Pivot tables to highlight different facts about the database. 
* Data Conversion: Some of the algorithms don’t comply with numerical data. The non-numerical data in the database is required to be converted. 

## Model Building 
* used the “FlightDelaysTestingData.csv” data file to build models based on: 
*. Naïve Bayes (NB) model. 
* Classification and Regression Tree (CART): 
* Logistic Regression.
* Real-Time Prediction  

## Conclusion 
* In this project, we used three different machine-learning algorithms to predict flight delays. We evaluated the performance of these algorithms using confusion matrices, which helped us measure the number of True Positives, False Positives, True Negatives, and False Negatives.
* Our goal was to select the best-performing algorithm. Among the three models we tested, Logistic Regression stood out. It achieved the highest scores in two out of three evaluation metrics, with values exceeding 0.8.
* One important finding is that all models showed lower testing accuracy compared to training accuracy. This suggests that our models are not overfitting, and they can handle differences between the training and testing data effectively.
* Overall, Logistic Regression appears to be the most suitable algorithm for predicting flight delays in this dataset, offering promising results in terms of accuracy and performance. However, we remain open to testing alternative algorithms to further improve our predictions.
