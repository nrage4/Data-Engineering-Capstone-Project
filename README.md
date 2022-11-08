# Data-Engineering-Capstone-Project

Data Engineer Project Requirements:

ACME Corporation sells a number of products. As a part of their product expansion, the company added toothbrushes and toys to their product mix. We’ve been asked by the stake holders to product some insights based on the sample data that represents the entire set of data. In particular, the stake holders want to understand:

1)	Which product offering is performing better
2)	Provide information on user demographics (age range, region) would help them hone in on marketing spend
3)	Are the sales seasonal or does it remain consistent throughout the year
4)	In the year 2021, our nationwide marketing spend was £200,000,000. Marketing activities covered the following regions - UK South East, UK North East, UK North, UK South. Can we justify the spend or was it a wasteful expenditure?
5)	We need to find out by region if our CPA – cost per acquisition is higher or lower than the average as per the research found on https://mystaticwebsite-3.s3.amazonaws.com/index.html


Technical aspects:

The operations team has put together a sales report in CSV format and uploaded the report to Amazon S3 – the file is publicly accessible and is at this location: https://mystaticwebsite-3.s3.amazonaws.com/test-data.csv 


Project Structure:

1) Data Gathering
This involves importing the dataframe and reviewing the data to determine whether any data cleaning was necessary

2) Data Cleaning

The data cleaning involved:
- finding the null values and dropping them
- change the negative values to positve values
- splitting the month and year into two different columns to make it more readable
- saving the clean data

3) Data Visualisation

Created graphs to visualise data to compare data for different questions


4) Webscraping / data cleaning

Web scraped the index.html and cleaned the scraped data to create a table

