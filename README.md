# Unicorn Companies

![](unicorn.jpg)

## Introduction 

According to google, **Unicorn companies** are those that reach a valuation of **$1 billion** without being listed on the stock market. This means that has its valuation equal to or greater than One Billion Dollars. It may take a few years or might take more than 50 years. This dataset gotten from Maven.com shows more than a thousand companies with their location (city and country), present valuation in dollars, seed capital (Total amount raised across all funding rounds to start the business), date when the company was founded and when it attained Unicorn and so on. The data was a bit messy but I cleaned it up, added some columns and transform some columns on the table 
**_Disclaimer_**: _All datasetand reports do not represent any company, institution or country_

## Problem statement

•	Which unicorn companies have had the biggest return on investment?

•	How long does it usually take for a company to become a unicorn? Has it always been this way?

•	Which countries have the most unicorns? Are there any cities that appear to be industry hubs?

•	Which investors have funded the most unicorns?

## Skills / Concept Demostrated

the following Power Bi features were incorporated:
- Bookmarking
- DAX,
- Quick measures,
- Modelling,
- filters,
- Group and Unpivot column,
- Button etc.


  ## Modelling

  The cardinality of the two table is many to many

  ![](model.png)


## Data sourcing

I downloaded the unicorn company csv file on the Maven website and then extracted it into Power Bi for cleaning, analysis and visualization.
It contains only one table but I referenced the table for analysis

## Data transformation / cleaning
Data was efficiently cleaned and transformed with Power Query Editor of Power BI. Some of the applied steps include
•	Creating new columns to store extract the year each company joined unicorn list in order for me to be able to calculate the year it takes to join the list 
Year founded – Year joined = duration it takes to achieve unicorn

  ![](model.png)
•	Also, a column was conditional formatted to give either after millennium or before millennium. Companies founded on or before 1999 was assigned before millennium while companies founded after 1990 are assigned after millennium. This was done to show disparity between companies founded before and after internet
•	I adjusted all value types of most columns and also write all currency figures in full
•	I referenced my to give me exact replica of my table so as to analyse all investors that was merged together.

