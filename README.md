# Real_Estate_Industry_Analysis

The goal of this project is conducting an in-depth analysis of public US firms within the real estate industry using various data analyses and natural language processing (NLP) techniques
that we learned in our course. The project utilizes three datasets.</br>
● public_firms.csv</br>
● major_groups.csv has all industry information</br>
● 2020_10K_item1_full.csv which is the major dataset containing all 10k information of all companies.</br>

Using these datasets, we investigated the real estate industry and generated valuable insights
using several techniques. First we processed these data for ETL, and did some descriptive
analysis such as data visualization and to have a better understanding of the dataset. After that,
we conducted text analysis on the 10-k data set for keywords analysis using wordcount, TF-IDF
and word cloud methods. Also , we transform words to vectors using a trained word embedding
model. In the final part, with the help of word2vec and the word embedding model, we found
two similar company and compared their key financial performance such as ROA and stock
sales. We also gave business insights and corresponding suggestions for the companies.
Here are some norms and punctuations we used in the following parts.</br>
● ‘fyear’ is the column name of fiscal year</br>
● ‘comn’ is the column name of company name</br>
● ‘prcc_c’ is the column name of average stock price for a certain company in a fiscal year.</br>
● ‘gvkey’ is the unique key for each company in ‘public_firm.csv.</br>
● ‘cik’ is the unique key for each year of each company in ‘ item_10k’.</br>
