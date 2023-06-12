# Smartphone Price Prediction on Flipkart

This project aims to develop a data-driven solution for predicting smartphone prices on the Flipkart platform. By leveraging web scraping techniques, we collected a dataset comprising 910 records and 8 attributes from the website. Using this data, we implemented powerful machine learning models to accurately forecast smartphone prices.

## Project Overview

The main objectives of this project are as follows:

1. Web Scraping: We utilized web scraping techniques to extract relevant data from the Flipkart website. This process ensured the accuracy and integrity of the collected data.

2. Data Preprocessing: The extracted data was preprocessed to remove any inconsistencies, missing values, or outliers. This step involved cleaning, transforming, and normalizing the data to make it suitable for machine learning models.

3. Model Development: We developed multiple machine learning models to predict smartphone prices. The models used in this project include:

   - K-Nearest Neighbors (KNN)
   - Linear Regression
   - Random Forest
   - Decision Tree
   - Gradient Boosting
   - Support Vector Machines (SVM)

4. Model Evaluation: The performance of each model was rigorously evaluated using essential metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R Squared (R^2). These metrics helped us identify the top-performing model.

5. Model Selection: Based on the evaluation results, we selected the model with the highest accuracy rate. In this case, the Logistic Regression model achieved an exceptional accuracy rate of approximately 97%.

## Tech Stack

The following technologies were used in this project:

- Python: The primary programming language for implementing the solution.
- NumPy: A Python library for numerical computing, used for handling arrays and mathematical operations.
- Pandas: A powerful data manipulation and analysis library, employed for data preprocessing tasks.
- Beautiful Soup: A Python library for web scraping, utilized to extract data from the Flipkart website.

## Dataset

The dataset used in this project consists of 910 records and 8 attributes related to smartphones on Flipkart. The attributes include:

1. name
2. memory
3. display
4. camera
5. power
6. price
7. discount
8. rating

## Getting Started

To reproduce the results of this project, follow these steps:

1. Clone the repository: `https://github.com/harish2020a/Flipkart-Smartphone-Price-Prediction-Leveraging-Web-Scraping.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Execute the data scraping cells, run the data preprocessing cells and Train and evaluate the machine learning models: `Python_Notebook.ipynb`
4. Analyze the evaluation results and select the top-performing model.
5. Use the selected model to predict smartphone prices.

Please note that you may need to modify the scripts according to your specific requirements, such as the website structure or dataset attributes.

## Conclusion

This project demonstrates proficiency in data scraping, preprocessing, model development, and evaluation to deliver a comprehensive solution for smartphone price prediction on Flipkart. By utilizing machine learning algorithms, we achieved accurate forecasts for smartphone prices, enhancing decision-making capabilities for buyers and sellers on the platform.
