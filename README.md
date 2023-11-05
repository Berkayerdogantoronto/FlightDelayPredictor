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
  
## Use Testing Data

I Made up five new rows (instances) of data and store them in a new file
“FlightDelaysTestingData.csv”.
