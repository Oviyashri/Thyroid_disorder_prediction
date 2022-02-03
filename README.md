# Thyroid Disorder Prediction
Thyroid disease is a common cause of medical diagnosis and prediction, with an onset that is difficult to forecast in medical research. The thyroid gland is one of our body's most vital organs. Thyroid hormone releases are responsible for metabolic regulation. Hyperthyroidism and hypothyroidism are one of the two common diseases of the thyroid that releases thyroid hormones in regulating the rate of body's metabolism. The main goal is to predict the estimated risk on a patient's chance of obtaining thyroid disease or not.

## About Dataset
From Garavan Institute

Documentation: as given by Ross Quinlan
 
6 databases from the Garavan Institute in Sydney, Australia


Approximately the following for each database:

  *	2800 training (data) instances and 972 test instances
  
  *	Plenty of missing data
 
  *	29 or so attributes, either Boolean or continuously-valued

2 additional databases, also from Ross Quinlan, are also here
 
 *	Hypothyroid.data and sick-euthyroid.data
 
 *	Quinlan believes that these databases have been corrupted

 *	Their format is highly similar to the other databases

1 more database of 9172 instances that cover 20 classes, and a related domain theory

Another thyroid database from Stefan Aeberhard

*	3 classes, 215 instances, 5 attributes

*	No missing values

A Thyroid database suited for training

*	3 classes

*	3772 training instances

URL: https://archive.ics.uci.edu/ml/datasets/thyroid+disease

## Approach

**Data Description:**
We will be using Thyroid Disease Data Set present in UCI Machine Learning Repository. This Data set is satisfying our data requirement. Total 7200 instances present in different batches of data. Here we will be exporting all batches of data from database into one csv file for training.

**Data Splitting:**
We split the data here for our train and test data for further uses.

**Data Preprocessing:**
We first explore our data set and we have to replace  null values, dropping some column, handling imbalanced data etc.

**Model Training:**
We trained various model in our notebook and Random Forest Classifier was good on it. We trained with our processed data.

**Model Evaluation:**
Model evaluation done by classification and report was saved.

**Model Saving:**
We will save our models so that we can use them for prediction purpose. 

**Push to app:**
Here we will do cloud setup for model deployment. We also create our flask app and user interface and integrate our model with flask app and UI.

**Data from client side for prediction purpose:**
Now our application on cloud is ready for doing prediction. The prediction data which we receive from client side. 

**Data processing:**
Client data will also go along the same process Data pre-processing and according to that we will predict those data.

**Export Prediction to CSV:**
Finally when we get all the prediction for client data, then our final task is to export prediction to csv file and hand over it to client.

## Web Deployment

Thyroid disease detection Web App: https://thyroid-disease-prediction-api.herokuapp.com

## Screenshots
**UI:**

![image1](https://user-images.githubusercontent.com/92749977/150357887-4491993b-6478-412d-9aa2-3bf9e8429602.jpg)

**Prediction:**

![image3](https://user-images.githubusercontent.com/92749977/150358057-2cc5bf3f-0c56-49a0-8b35-9f3c49c440a2.jpg)

![image4](https://user-images.githubusercontent.com/92749977/150359302-65ddd462-9fe6-40bb-b139-365c1f02286c.jpg)

## Project Documents

## High Level Design 

URL: https://github.com/Oviyashri/Thyroid_disorder_prediction/blob/main/docs/HDD.pdf

## Low Level Design

URL: https://github.com/Oviyashri/Thyroid_disorder_prediction/blob/main/docs/LLD.pdf

## Architecture

URL: https://github.com/Oviyashri/Thyroid_disorder_prediction/blob/main/docs/Architecture.pdf

## Detailed Project Report

URL: https://github.com/Oviyashri/Thyroid_disorder_prediction/blob/main/docs/DPR.pdf

## Wireframe

URL: https://github.com/Oviyashri/Thyroid_disorder_prediction/blob/main/docs/Wireframe.pdf

## Demo Video

URL: https://drive.google.com/file/d/1u5mHOd3V9vxg5H6P2h63ZqUHikj53ZNX/view?usp=sharing
	
https://user-images.githubusercontent.com/92749977/150366444-d137e97c-2097-447a-b969-c5e1f9649ce8.mp4

## Author

Oviyashri B [LinkedIn](https://www.linkedin.com/in/oviyashri-balasubramaniam)
