# OIBGRIP
Customer Data Analysis and Prediction

Introduction:

In today’s competitive business environment, leveraging data to drive decision-making is crucial for enhancing customer engagement and satisfaction. This project focuses on developing a predictive analytics model to anticipate customer behavior and preferences using machine learning techniques. By analyzing historical customer data, the project aims to provide actionable insights that can help businesses tailor their marketing strategies, personalize customer interactions, and ultimately drive revenue growth.

Objective:

The primary goal of this project is to build a predictive model that can forecast customer needs and behaviors. The model will be used to optimize marketing campaigns, improve customer experience, and increase overall business performance.

Files Included:

predictive_analytics.ipynb: The main Jupyter Notebook containing the analysis and predictive modeling code.
customers-1000.csv: The dataset used for analysis and model training.
About the dataset:

The dataset contains detailed information about customers, including unique identifiers (Customer Id), personal details (First Name, Last Name), and contact information (Phone 1, Phone 2, Email). It also includes business-related data such as the customer's company, geographical location (City, Country), and subscription details (Subscription Date, Website). This rich set of features allows for comprehensive analysis of customer demographics, contact methods, geographical distribution, and engagement trends, facilitating targeted marketing, customer segmentation, and predictive modeling for enhancing business strategies.

Instructions:

Setup
Ensure you have the necessary Python libraries installed. You can install them using pip:

pip install pandas matplotlib seaborn numpy scikit-learn
Load the Dataset

Download and extract the zip file containing this README, the Jupyter Notebook, and the dataset file.

Place the dataset file (customers-1000.csv) in the same directory as the Jupyter Notebook (predictive_analytics.ipynb).

Run the Notebook

Open the Jupyter Notebook (predictive_analytics.ipynb) in Jupyter Lab or Jupyter Notebook.

Execute the cells sequentially to load, analyze, and model the dataset.

Data Analysis and Visualization

Histogram of Subscription Dates: Shows the distribution of subscription dates.
Bar Chart of Customer Counts by City: Displays a count of customers in each city (sampled).
Scatter Plot of Subscription Date vs. Company: Illustrates the relationship between subscription dates and company names .
Pie Chart of Customer Distribution by Country: Visualizes the distribution of customers across different countries (sampled).
Feature Engineering and Modeling
Feature Engineering:

Created a CityGroup feature based on city frequency.
Created a proxy target variable HasPhone2 indicating the presence of 'Phone 2'.
Modeling:

A logistic regression model is used to predict the presence of 'Phone 2'.
The dataset is checked for class balance, and if necessary, balanced by sampling.
Results
The predictive_analytics evaluates the model's performance using accuracy, precision, recall, and F1-score.
Cross-validation is performed to ensure the model's robustness.
