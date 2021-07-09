# Landslide-Prediction

This project was done during my summer internship under Associate Prof. Gagan Raj Gupta at IIT - Bhilai

--> Automated crowdsourcing of data from various resources about landslides in india with the help of general and focused crawler with the help of self made JSON configuration file.

--> We then automated preprocessing the data using different methods such as NLP techniques , hard coding to remove irrelevant data from Youtube dataset. Also if queries were in hindi language, it gets converted into english.

--> Youtube Dataset was then used to Rank important keywords using YAKE library so as to do more research about some particular landslide event using our focused crawler.

--> I used the data that my teammates collected from NASA inventory to do analyse data and finding which districts has most no. of landslides and then made another datasets for top 5 districts further for binary classification

--> For classification , Explanatory variables were Rainfall data , Month and elevation to do binary classification using various Machine Learning and Deep Learning Algorithms. 

--> We also are currently working on developing novel NLP model to Extract Facts and location from the GSI dataset and other inventories. I also Improved time complexity using implementation of TRIE data structure to have faster location extraction. 
