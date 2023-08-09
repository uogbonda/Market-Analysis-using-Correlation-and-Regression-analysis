# Market-Analysis-using-Correlation-and-Regression-analysis

Regressionn on Customer dataset with number of purchases from catalog, stores etc: Customer Segmentation using Education status.

## Table of Content
* [General info](#general-info)
* [Technologies](#technologies)
* [Methods](#methods)
* [Key Findings](#key-findings)

## General info
A dataset containing the details of loyal clients, and their purchase behaviour. The clients purchased items such as fish, meat, and wine from a company. Regression and Correlation analysis is performed on the dataset to predict the best ways to campaign to their loyal customers be it through sending catalogs, information on what is in the store, or what is offered on the website.

<b> A Exploring and Understanding basics data </b>

1. Know the data distribution across the education category.
2. What are the different sales associated with their purchases (Using Categorical Mean)

<b> B Statistical Analysis - Answering the Questions</b>
1. The impact of the number of purchases on Sales (Using Correlation and Regression).

2. How web, store and catalog purchases can affect sales (Broken down Question 1 and Question 2 based on Account Type(Education))


## Technologies
Project performed on:
* Python.
* MySQL.
* Google Colab.


## Methods

The method implemented was carried out by:
* Querying the data using MySQL database to get the more information and saved in csv file.
* Loaded csv file on Google Colab.


## Key Findings

The findings show the following:
*  Master: These clients have positive correlation with purchasing from the store and Catalogs. for each dollar of sales, there is a ROI of 129 US dollar from Catalog,    75 US dollar ROI from store purchases.
* Purchases from catalog gives high ROI across the 5 Account type(ie Graduatiion,PhD,Basic,2nCyle and Masters)
* Clients with Basic education do not have a particular campaign that appeals to them. Without using any campaigns for Basic clients, we get 0.03 unit sales.
* Accepted campaigns are 5,1,4 and last campaign(Response) for Graduation.
* Only Campaign 5 and Response for PhD.
* 2n Cycle: These are clients in their 2nd level in university. Only campaign 5,1 and 4 is best.
* Only campaign 5 and 1 works for Master.
