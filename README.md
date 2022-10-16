<h1 align="center"><font color='blue'>Data-Engineering-Credit-Card-Transactions</font></h1>


<h3 align="left"><font color='blue'>Project Description</font></h3>

This project is a case study for a credit card company to determine the level of transactions over time and for what services are primarily related. 

To do this, we will be using the following data sets:

- [Credit Card Transactions](https://www.kaggle.com/datasets/ealtman2019/credit-card-transactions)
- [Geographical Name Location Data](https://www.census.gov/)
- [Daylight Data](http://api.timezonedb.com/v2.1/get-time-zone?time=2018-01-01&key=yourapikey&format=json)

<h3 align="left"><font color='blue'>Domain Background</font></h3>

This project looks to define and understand whether or not there is any correlation between the factors listed above. It will also address whether or not there is an association with these factors and if the correlations are proportional. 

It will investigate what kind of shape these trends are, whether it is linear, logarithmic or exponential. 

Additionally, we'll take a look to determine whether there are any outliers or seasons in which there is an anomaly in either amount or type of transaction. 

## Problem Statement & Goal

The goal of this project is to use facts from the three data sets that are listed below to find:
- What are the trends over time for types of transactions and in what amout of money exchanged
- What are the types of industries national that rely on credit card transactions
- Are there any seasons or significant events when volume is equally or unequally affected by credit card usage? For example, does a holiday affect when a credit card is used the most.
 
## Datasets and Inputs

There are three datasets to leverage for this project. These three deataset are located in the ./datasets/raw folder. Two of this datasets come from Kaggle and the other dataset comes from a government site.

- ./datasets/raw/CT-account-20180827_1.csv 
    - Account and customer Id which will be used to combine two datasets

- ./datasets/raw/CT-transaction-20180827_1.csv

    - Transaction Id, Accoun Id, amount and Date of Transaction

- ./datasets/raw/Canadian.txt

    - Contains national addresses and geographic coordinates


## Solution Statement & Approach

The approach will be to first combine the three datasets into a single fully normalized file. The columns will be re-named in a way that will clearly describe the data. Then columns will be converted into usable forms and the data will be modelled for clarity.

Once the dataset is cleaned, shaped and normalized, a data dictionary will be added to provide a clear table of what each column represents. From there a vesion of the dataset can be used for etl, histogram (analysis) and graphing (Visualization) purposes.

Python is the primary tool used in this project.

## Benchmark Model

There is no benchmark model for this project. We are __not__ attempting to create one. We are, however, creating something completely new.

## Evaluation Metrics

There is no evaluation model for this project. We are __not__ attempting to create one. We are, however, creating something completely new.

## Project Design

The final datasets will be normalized and consist of the following columns: 
- id
- customerid
- accountid
- date
- amount
- industry
- longitude
- latitude
-
## Deployment

To deploy this project to be used by the client, a data dictionary will be created and attached to the dataset.

Once the dataset and maps are complete, the project can be used.

## Ethics & Privacy

The project does not include any sensitive information that the client does not already have.






The company wants to know how customers use their credit cards, how they manage their credit limit, and how they pay their bills. The company also wants to know how payment habits vary across geographic regions and between 