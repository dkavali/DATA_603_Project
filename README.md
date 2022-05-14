#                                                                          Amazon Sentiment Analysis 

## *Project Overview*

In this project, we use Sentimental Analysis to predict whether a review is 'Positive,' 'Neutral,' or 'Negative' based on reviews on a million goods from Amazon's products, Amazon sentiment dataset and Amazon Electronics datasets. 

To better understand the Amazon data, we analysed 3 datasets - 
1. Amazon 2022 products
2. Amazon Electronics Products
3. Amazon Sentiment Dataset

Intially we are starting with Amazon products dataset and we used tools like MongoDB to store the data into 3 different databases. We are accessing the data with the help of SparkSQl into the Spark dataframe using pyspark on the jupyter notebook.

The first dataset - *Amazon Product Dataset* has products like Toys, Vehicles, Jewellery etc. We have performed the Extract, Transform and Loading operations on this dataset and made the data feasible for Exploratory Data Analysis. After further analysis and cleaning, storing the data into the .csv file using the pandas library. 



## *Source of Dataset*

https://www.kaggle.com/nguyenngocphung/10000-amazon-products-dataset

## *Problem Statement*

Amazon Reviews will be misleading as the content may be subjective(positive or negative) and sometimes may lack the information. Finding out whether the review is positive, negative or neutral is a critical task. 


## *Bigdata Tools*

We have used the following bigdata tools:
1. MongoDB
2. Apache Spark
3. QlikSense
4. Tableau
5. Anaconda Navigator

## *Steps to run the file*

We have 2 files to run - 
1. With a sentiment dataset and word cloud visualizations - This can be executed as normal .ipynb file
2. Second file is required to have MongoDb connection as the data is retrieved from MongoDb in the notebook. This notebook will also need Apache Spark as it is coded in Apache Spark. 



