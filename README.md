# Competitive-Intelligence-1
This project uses Sentiment Analysis and Topic Modelling for Competitive intelligence in E-Commerce

Author and Contributor List
---------------------------
Afolabi Ibukun

Eniola Enilolobo

Project Description
-------------------
The first goal of our analysis was to study the competitive environment and obtain insights that could draw in more customers. This was carried out in two phases:
1.	Analyzing customer sentiments on the Facebook posts of the case study (Afrimash) and their competitors also.
2.	Performing topic modeling, also from the Facebook posts of the case study and their competitors.

Data Source
------------
The first step in analyzing the sentiments of customers of both Afrimash and their competitors is to gather data from their respective Facebook pages was gathered. Using FacePager, a data-gathering tool, comments from their respective posts on Facebook within the last two years (from 22/02/2019 to 23/06/2021) were extracted. The data extracted from FacePager was unfit for analysis as it was a direct copy of what the FacePager interface looked like (that is, apart from the extracted data, it also comprised other unnecessary information like the object ID, key, type, query Id, etc.). To clean up the extracted data, Python was used. 

Data Preprocessing
------------------
The extracted data was preprocessed in python (link the file)

Sentiment Analysis
------------------
In analyzing the customer sentiments, sentiwordNet in Rapidminer was used. 

Sentiment Visualization
-----------------------
The results gotten was visualized in python (link the file)

Topic Modeling
--------------
LDA ALgorithm was then applied and visualized (https://github.com/ibkAfolabi/Competitive-Intelligence-1/blob/main/LDA_analysis_on_facebook_posts.ipynb)


