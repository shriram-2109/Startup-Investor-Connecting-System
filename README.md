## Startup-Investor Connecting System

## Prerequisites for the project : 
 * You need to have a postgre database created with the values of the Indian Startup.csv file loaded into it.
 * Install all required libraries

## Working of our project : 

We connect SQL database(PostgreSQL) with our /code app.py file which is then preprocessed and the data is used in our machine learning model.

![database](https://github.com/shriram-2109/Startup-Investor-Connecting-System/blob/main/images/database.png)


The same preprocessed data is used as training dataset for our machine learning algorithm.

In this algorithm we take in 2 or more feataures of the data set and derive a similarity matrix comparing those constrains(Cosine similarity) to find the most accurate/similar startups for the investors.

The front end of this project is done mostly with streamlit module of python database from postgreSQL and streamlit is connceted using psycog2.

![home](https://github.com/shriram-2109/Startup-Investor-Connecting-System/blob/main/images/home.png)
![input](https://github.com/shriram-2109/Startup-Investor-Connecting-System/blob/main/images/input.png)

## Output :

![out1](https://github.com/shriram-2109/Startup-Investor-Connecting-System/blob/main/images/out1.png)
![out2](https://github.com/shriram-2109/Startup-Investor-Connecting-System/blob/main/images/out2.png)
![out3](https://github.com/shriram-2109/Startup-Investor-Connecting-System/blob/main/images/out3.png)

## Walkthrough :
[video.webm](https://github.com/shriram-2109/Startup-Investor-Connecting-System/blob/main/images/video.webm)
