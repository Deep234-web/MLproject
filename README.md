# Student Score Prediction - End-to-End Machine Learning Project

## Overview

The Student Score Prediction project is an end-to-end machine learning pipeline designed to predict student scores based on various features. This project encompasses the entire machine learning lifecycle, from data ingestion to model deployment. 

### Key Components

1. **Data Ingestion**: Collects data from a MySQL database, splits it into training and testing datasets, and saves these datasets as CSV files.
2. **Data Transformation**: Preprocesses the data by handling missing values, encoding categorical variables, and scaling numerical features.
3. **Model Training**: Trains and evaluates multiple regression models, selecting the best-performing model based on evaluation metrics.
4. **Model Deployment**: Deploys the trained model using AWS Elastic Beanstalk and sets up a continuous integration and deployment pipeline with AWS CodePipeline.

## Features

- **Data Collection**: Automated ingestion of student data from MySQL.
- **Preprocessing**: Data cleaning, encoding, and scaling.
- **Model Training**: Training of various machine learning models and selection of the best one based on performance.
- **Deployment**: Deployed on AWS Elastic Beanstalk with automated deployment through AWS CodePipeline.

## Deployment

The application has been deployed on AWS Elastic Beanstalk with a continuous integration and deployment pipeline using AWS CodePipeline. You can access the live application at:

[AWS Deployed Application - Student Score Prediction](http://studentscoreprediction-env.eba-zq5zfp6y.us-east-1.elasticbeanstalk.com/predictdata)


## Author
Deep Rajani

Email: deeprajani1999@gmail.com

Feel free to reach out for any questions or suggestions!
