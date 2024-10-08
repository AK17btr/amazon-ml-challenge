# Amazon-ml-challenge 2023
![68747470733a2f2f65787465726e616c2d636f6e74656e742e6475636b6475636b676f2e636f6d2f69752f3f753d68747470732533412532462532466d656469612d666173746c792e6861636b657265617274682e636f6d2532466d656469612532466861636b6174686](https://github.com/user-attachments/assets/a035380a-4b0b-48ed-a3fe-f6212c437ac1)


A team-participation challenge was held on April 21, 2023, 12:00 AM IST–April 23, 2023, where a solution was to be built for the given problem statement. This repository consists of a Jupyter notebook that contains the code we submitted under the name of our team, TALISMANIC VADERS and with an accuracy of 20.42677, we ranked 290 among 4898 teams.

# Problem Statement
Product length prediction
In this hackathon, the goal is to develop a machine learning model that can predict the length dimension of a product. Product length is crucial for packaging and storing products efficiently in the warehouse. Moreover, in many cases, it is an important attribute that customers use to assess the product size before purchasing. However, measuring the length of a product manually can be time-consuming and error-prone, especially for large catalogues with millions of products.

You will have access to the product title, description, bullet points, product type ID, and product length for 2.2 million products to train and test your submissions. Note that there is some noise in the data.

# Task
You are required to build a machine-learning model that can predict product length from catalogue metadata.

# Dataset description
The dataset folder contains the following files:

train.csv: 2249698 x 6

test.csv: 734736 x 5

sample_submission.csv: 734736 x 2

# The columns provided in the dataset are as follows:

Column name	Description
PRODUCT_ID	Represents a unique identification of a product
TITLE	Represents the title of the product
DESCRIPTION	Represents the description of the product
BULLET_POINTS	Represents the bullet points about the product
PRODUCT_TYPE_ID	Represents the product type
PRODUCT_LENGTH	Represents the length of the product

# Evaluation metric
score = max( 0 , 100*(1-metrics.mean_absolute_percentage_error(actual,predicted)))
