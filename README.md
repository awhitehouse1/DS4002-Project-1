## Contents of Repository

## Section 1: Software and platform section
The majority of our code was written in Python using Google Colab's notebooks. Google Colab was used because it made sharing code simpler and it also allowed us to work on both Windows and Mac machines without any issues. In addition to using Python, some of our exploratory data analysis was also written in R. 

For add-on packages, the NLTK (Natural Language Tool Kit) and Vader Sentiment packages were used for sentiment analysis. Pandas was used for data processing and manipulations. Matplotlib and Seaborn were used for creating the visualizations.

## Section 2: A Map of your documentation
In our repository, there are folders for the data, scripts, and output. In the data folder, there is the original Amazon Product Review data source.
- In the data folder:
  - amazon_reviews: the original data source
- In the scripts folder:
  -  EDA1_3.ipynb: code used for exploratory data analysis, written in a python notebook
  -  EDA.pdf: code used for exploratory data analysis, written in R
  -  Vader.ipynb: code used to implement the VADER sentiment analysis and analyze the words most commonly associated with different ratings
- In the output folder:
  - file with our graphs

## Section 3: Instructions for reproducing our results
For reproducing the results, first git clone the github repository. To run the VADER sentiment analysis, run the Vader.ipynb file from the beginning in the Scripts folder. This will install all of the needed packages, preprocess the data to prepare for the sentiment analysis, and then implement the sentiment analysis. 
