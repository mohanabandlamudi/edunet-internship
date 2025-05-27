## Employee Burnout Prediction Using Artificial Intelligence

💡 Overview


This project focuses on predicting employee burnout using machine learning techniques. Burnout is a critical issue in today’s fast-paced work environments, affecting employee well-being, productivity, and organizational health. The goal is to build a system that can help HR teams and organizations proactively identify at-risk employees and take timely action.

📌 Objectives


✅ Analyze factors contributing to employee burnout.

✅ Build and evaluate predictive machine learning models.

✅ Visualize trends and burnout risk levels.

✅ Provide actionable insights to improve employee engagement and satisfaction.

## Technologies Used
Category	Tools & Libraries
Programming	Python
ML Libraries	Scikit-learn
Data Processing	Pandas, NumPy
Visualization	Matplotlib, Seaborn, Plotly
IDE/Notebook	Jupyter Notebook
Version Control	Git, GitHub


## About Dataset
Context
Understanding what will be the Burn Rate for the employee working in an organization based on the current pandemic situation where work from home is a boon and a bane. How are employees' Burn Rate affected based on various conditions provided?

Content
Globally, World Mental Health Day is celebrated on October 10 each year. The objective of this day is to raise awareness about mental health issues around the world and mobilize efforts in support of mental health. According to an anonymous survey, about 450 million people live with mental disorders that can be one of the primary causes of poor health and disability worldwide. These days when the world is suffering from a pandemic situation, it becomes really hard to maintain mental fitness.

Employee ID: The unique ID allocated for each employee (example: fffe390032003000)


Date of Joining: The date-time when the employee has joined the organization (example: 2008-12-30)


Gender: The gender of the employee (Male/Female)


Company Type: The type of company where the employee is working (Service/Product)


WFH Setup Available: Is the work from home facility available for the employee (Yes/No)


Designation: The designation of the employee of work in the organization.
In the range of [0.0, 5.0] bigger is higher designation.


Resource Allocation: The amount of resource allocated to the employee to work, ie. number of working hours.
In the range of [1.0, 10.0] (higher means more resource)


Mental Fatigue Score: The level of fatigue mentally the employee is facing.
In the range of [0.0, 10.0] where 0.0 means no fatigue and 10.0 means completely fatigue.


Burn Rate: The value we need to predict for each employee telling the rate of Bur out while working.
In the range of [0.0, 1.0] where the higher the value is more is the burn out.


## Workflow
1. Data Cleaning & Preprocessing

- Handle missing values

- Encode categorical features

- Normalize/scale numerical data

2. Exploratory Data Analysis (EDA)

- Understand distribution and correlation of features

- Visualize patterns in employee burnout

Model Building

- Train Linear Regression Model

3. Model Evaluation

- Metrics: Mean Squared Error, Root Mean Squared Error, Mean Absolute Error, R-squared Score

4. Insights & Visualization

-Identify key burnout indicators

- Interactive dashboards and heatmaps
