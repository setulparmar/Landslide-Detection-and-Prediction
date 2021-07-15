# Landslide-Prediction

This project is in progress currently in my summer internship under Associate Prof. Gagan Raj Gupta at IIT - Bhilai

--> Daily crowdsourcing from youtube and twitter about landslides in india using general and focused crawler with the help of JSON configuration file.

--> Further,did the data preprocessing using different methods of NLP techniques , hard coding to filter out irrelevant data from Youtube dataset.

--> Youtube Dataset was then used to do data analysis and clustering using pre trained sentence transformer models and unsupervised approach.

--> Then extracted keywords with their ranks using YAKE library so as to do more research about some important landslide event using focused crawler.

--> Further did binary time series classification per district for top 5 districts where landslides occurs the most.

--> For classification , Explanatory variables were Rainfall data , Month and earthquake data where applied various machine Learning and designed deep Learning algorithms to predict whether there will be landslide or not. 

--> We also are currently working on developing novel NLP model to Extract Facts and location from the GSI dataset and other inventories. Also improved time complexity using implementation of TRIE data structure to have faster location extraction. 

Note : Daily automatic collection and filtering was there with the help of scheduling in deepnote.com
