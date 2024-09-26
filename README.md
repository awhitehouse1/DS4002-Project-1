## Contents of Repository

## Section 1: Software and platforms
The majority of our code was written in Python using Google Colab's notebooks. Google Colab  made sharing code simpler and also allowed us to work on both Windows and Mac machines without any issues. In addition to using Python, some of our exploratory data analysis was in R using RStudio. 

For add-on packages, the NLTK (Natural Language Tool Kit) and Vader Sentiment packages were used for sentiment analysis. Pandas was used for data processing and manipulations. Matplotlib and Seaborn were used for creating the visualizations. We also used tidyverse and ggplot2 for R. 

## Section 2: Map of documentation
In our repository, there are folders for the data, scripts, and output. The original Amazon Product Review data source is located in the data folder. The contents of each folder are described below. 
- In the data folder:
  - amazon_reviews.csv: original data source
  - amazon_reviews_with_compound_scores.csv: contains the compound sentiment scores for each review, along with its positive, negative, and neutral sentiment scores
  - DataAppendix.pdf: includes tables, figures, and other descriptive statistics about the data
- In the scripts folder:
  -  EDA1_3.ipynb: code used for exploratory data analysis, written in a python notebook
  -  EDA.pdf: code used for exploratory data analysis in R Markdown
  -  Vader.ipynb: code used to implement the VADER sentiment analysis and analyze the words most commonly associated with different ratings
- In the output folder:
  - BarPlots_Most_Frequent_Words_by_Rating.pdf: shows the top ten most commonly used words for each overall rating (1-5)
  - BoxPlot_Compound_Score_by_Overall_Rating.png: shows the compound sentiment score distribution for each overall rating (1-5)
  - Correlation_Compound_Score_and_Overall_Rating.png: scatterplot and line of best fit showing the correlation between compound sentiment score and overall rating
  - Correlation_Median_Compound_Score_and_Overall_Rating.png: scatterplot and line of best fit showing the correlation between the median compound sentiment scores for each rating and the overall rating
  - HeatMap_Most_Frequent_Words_Normalized.png: heatmap of the ten most commonly used words for each rating
  - RidgelinePlot_Compound_Score_by_Overall_Rating.png: rigidline plot showing the distribution of compound sentiment score by overall rating

## Section 3: Instructions for reproducing our results
First, open your terminal and git clone the github repository. Navigate to the Scripts folder and run the Vader.ipynb file for VADER sentiment analysis. This will install all of the needed packages, preprocess the data to prepare for the sentiment analysis, and then implement the sentiment analysis. 
