# Project 2 - Text Analysis
This is the template for the second project for ECON1680: Machine Learning, Text Analysis, and Economics. This project is meant to be an economic application of machine learning. Over the course of the project, you should fill in the following sections of the Readme.md file below with your research question and motivation, your data sources, your methods, your results, and instructions for replciation.
## Research Question
How have mainstream U.S newspapers’ sentiments and representations of the Middle East changed over time? How is sentiment predictive of US government spending on wars in the Middle East?  
## Data
Newspaper data from Proquest and military spending data from FRED. 
## Method
Bag of words techinques like word count and TFIDF and using sentinet dictionary in order to get a sentinment score for each document. OLS regressions. 
## Results
I found that the effect of sentinment on military spending is not statistically different from zero. 
## Replication Instructions
Download a random set of newpapers in the years 1980-2021 from the USA. Use the abstract to create document term matrix using word count and TFIDF. Get summary statistics. Use word lists like sentiwordnet to get the number of postive and negative words. Run the differnet sentinment scores, from the different methods in a regression with the y variable being military spending as a fraction of GDP. Set a two and one quarter lag in the sentinment scores.