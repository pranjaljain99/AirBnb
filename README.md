# AirBnb   
## 1.Problem definition   
This is a small project to extract the insights from the AirBnB dataset.   

## 2.Data source identification, selection and extraction
### Dataset Source : insideairbnb.com. The download link is
http://data.insideairbnb.com/united-kingdom/england/london/2019-07-10/data/listings.csv.gz

## 3.Data cleaning and transformation
The dataset consists of 83850 dimensions and 106 features from 3 countries as seen from the dataset - UK/Spain/France. 

## 4.Data exploration and Visualization results
#### 1. Data Cleaning and EDA.ipynb	- 
Getting a feel of the data, Exploring features, finding the Nan values from the dataset, finding t=out which are the independent variables and which are the dependent variables. 
I tried to analyse the number of Customer Accomodations, Analysing Reviews, Analysing Room & Property Types and Bed types and used visualization techniques to explore the data.

#### 2. More Exploration and Feature Engineering.ipynb	
In this notebook, I tried to utilize the features like the neighbourhood, the target variable 'Price', and creating a wordcloud from the summary of the listings.  

## 5.Choosing modelling approach & Model development
#### 3. Predicting similar listings using knn.ipynb 
Here I tried to use the summary feature to use text timing using TfidfTransformer and using K nearest neighbours. Although a better analysis could have been done if review summary was availible at customer level instead.

4. modelling.ipynb
