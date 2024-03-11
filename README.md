# Sentiment Analysis Web App Using PyTorch and Amazon SageMaker
This project demonstrates a comprehensive deep learning workflow, focusing on creating a sentiment analysis web application. The core functionality of this application allows users to input a movie review text on a web interface, which is then processed by a backend model to predict the sentiment of the review. This prediction is subsequently displayed on the web page, providing an interactive experience.

## Table of Contents
- [Project Workflow Overview](#project_workflow_overview)

- [Reference](#reference)

## Project Workflow Overview
1. Data Acquisition: Retrieve the dataset containing movie reviews.
2. Data Preparation: Process and clean the data to make it suitable for training.
3. Data Uploading: Upload the processed data to Amazon S3 for model access.
4. Model Training: Utilize a suitable deep learning model and train it using the prepared dataset.
5. Model Evaluation: Test the model's performance to ensure its accuracy and reliability.
6. Initial Model Deployment: Deploy the trained model in a test environment for validation.
7. Model Interaction: Perform predictions using the deployed model to analyze its real-time performance.
8. Web Application Deployment: Integrate the trained model into a web application, enabling users to input reviews and receive sentiment predictions.

