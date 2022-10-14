# Cryptocurrencies
Using Unsupervised Machine Learning to Discover Unknown Patterns

## Background

### Overview of Analysis

This project consists of three technical analysis deliverables and a written report.

* Deliverable 1: Preprocessing the Data for PCA

* Deliverable 2: Reducing Data Dimensions Using PCA

* Deliverable 3: Clustering Cryptocurrencies Using K-means

* Deliverable 4: Visualizing Cryptocurrencies Results


### Purpose

Stakeholders are interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. So, we'll create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

The data we will be working with is not ideal, so it will need to be processed to fit the machine learning models. Since there is no known output for what we are looking for, we have decided to use unsupervised learning. To group the cryptocurrencies, we decided on a clustering algorithm. We’ll use data visualizations to share our findings with the board.

## Resources

Data source:

- (1) crypto_clustering_starter_code, (2) cryptocurrency data (crypto_data.csv)

Software:

- Python 3.9.10, Jupyter Lab 4.6, Visual Studio Code 1.71.2
 
<br/>

## Methodology

### D1: Preprocessing the Data for PCA 

Using your knowledge of Pandas, you’ll preprocess the dataset in order to perform PCA in Deliverable 2.

<br/>


### D2: Reducing Data Dimensions Using PCA

Using your knowledge of how to apply the Principal Component Analysis (PCA) algorithm, you’ll reduce the dimensions of the X DataFrame to three principal components and place these dimensions in a new DataFrame.

<br/>

### D3: Clustering Cryptocurrencies Using K-means

Using your knowledge of the K-means algorithm, you’ll create an elbow curve using hvPlot to find the best value for K from the pcs_df DataFrame created in Deliverable 2. Then, you’ll run the K-means algorithm to predict the K clusters for the cryptocurrencies’ data.

<br/>


### D4: Visualizing Cryptocurrencies Results

Using your knowledge of creating scatter plots with Plotly Express and hvplot, you’ll visualize the distinct groups that correspond to the three principal components you created in Deliverable 2, then you’ll create a table with all the currently tradable cryptocurrencies using the hvplot.table() function.

<br/>


## Results:

### D1: Preprocessing the Data for PCA 

#### Findings:

*

*

*

*

#### An accuracy score for the model is calculated:

![amazon_dataset_example](./)
 
<sub> Figure (1.1) RandomOverSampler balanced accuracy report

<br/>

#### A confusion matrix has been generated:

![amazon_dataset_example](./)
 
<sub> Figure (1.2) RandomOverSampler matrix

<br/>

 #### An imbalanced classification report has been generated:

![amazon_dataset_example](./)
 
<sub> Figure (1.3) RandomOverSampler imbalanced classification report

<br/>



### D2: Reducing Data Dimensions Using PCA

#### Findings:

*

*

*

*
 
#### An accuracy score for the model is calculated:

![amazon_dataset_example](./)
 
<sub> Figure (1.10) SMOTEEN balanced accuracy report

<br/>

#### A confusion matrix has been generated:

![amazon_dataset_example](./)
 
<sub> Figure (1.11) SMOTEENN matrix

<br/>


### D3: Clustering Cryptocurrencies Using K-means

#### Findings:

*

*

*

*

 #### An accuracy score for the model is calculated:

![amazon_dataset_example](./)
 
<sub> Figure (1.13) BalancedRandomForestClassifier balanced accuracy report

<br/>

 
### D4: Visualizing Cryptocurrencies Results

#### Findings:

*

*

*

*

 #### An accuracy score for the model is calculated:

![amazon_dataset_example](./)
 
<sub> Figure (1.13) BalancedRandomForestClassifier balanced accuracy report

<br/>


## Summary




#### The F1 values for our models:

*

*

*


 
To summarize our results, we'll focus 
 
*

*

In general the ....
 
For future evaluations we may want to ....


## References

[Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

[scikit-learn](https://scikit-learn.org/stable/)
 
[imbalanced-learn](https://imbalanced-learn.org/stable/)

