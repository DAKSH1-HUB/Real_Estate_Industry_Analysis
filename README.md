# Real_Estate_Industry_Analysis

The goal of this project is conducting an in-depth analysis of public US firms within the real estate industry using various data analyses and natural language processing (NLP) techniques
that we learned in our course. The project utilizes three datasets.</br>
● public_firms.csv</br>
● major_groups.csv has all industry information</br>
● 2020_10K_item1_full.csv which is the major dataset containing all 10k information of all companies.</br>

Link to 2020_10k_item1_full https://drive.google.com/file/d/1QR3Smb9yy0zAkCLeral34MuHGMWb9lRF/view?usp=share_link
</br>

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

Insights generated:-
![image](https://github.com/DAKSH1-HUB/Real_Estate_Industry_Analysis/assets/81084807/7a131c7b-211f-453b-b928-104567ef6648)
As seen from the chart, we can see there was a huge spike in stock price after the 2008 Financial
Crisis, Whole market is rebounding after the drop from 2007 and 2008. After 2013, the market
became more stable as the economy had recovered from the crash.

![image](https://github.com/DAKSH1-HUB/Real_Estate_Industry_Analysis/assets/81084807/4f43d71d-ea5c-40c3-9570-1ff9d5e0bc94)
The return on assets for the real estate industry remained close to zero before 1997. Then it has
been fluctuating in the range around 0 to -1 during 1998 to 2009. Then in 2010 it rose
dramatically because the house price rebounded after the financial crisis after 2008. Then the
return on assets went back to stay in the range a bit lower than zero until 2020.
![image](https://github.com/DAKSH1-HUB/Real_Estate_Industry_Analysis/assets/81084807/f0b6aa30-e2b0-4cd0-9f12-fade84f63783)

![image](https://github.com/DAKSH1-HUB/Real_Estate_Industry_Analysis/assets/81084807/1d74f87f-cd75-4ba0-9564-c54ca8a0b8b0)



Link to the collab file:- https://colab.research.google.com/drive/10s8tpBLRNEBMuk4Jw7SqZe7PbHIfK8dh?usp=sharing
