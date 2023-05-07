# Injuries in Construction Industry: Exploring Causes of Accidents Using Machine Learning

## Project Description
The IHSA has been using the dataset to keep track of the injuries and analyze the data accordingly. However, the injuries data are interpreted and reported based on their categories and no further data analysis into each injury type and cause are investigated. This project aims to provide the client with a service to suggest a data analysis process that implements a machine learning algorithm to analyze the dataset. The result from the analysis and the interpretation of the result, along with recommendations for the IHSA to optimize the utilization of the collected data, are included in this service. Although the IHSA covers a wide range of trade sectors, the client wants this project to focus only on the construction industry. 

## Project Objective
The purpose of this project is to develop a comprehensive data analysis service for the Infrastructure Health and Safety Association (IHSA) to identify leading factors contributing to injuries in the construction industry in Ontario. This service will assist the IHSA in making informed decisions on where to allocate resources to prevent or reduce injuries. 

## Partner
* Client: [The Infrastructure Health & Safety Association (IHSA)](https://www.ihsa.ca/)
* Supervisor: [Professor Greg A. Jamieson](https://www.mie.utoronto.ca/faculty_staff/jamieson/)

## Methods Used
* Data Cleaning, including filtering relevant data, correcting data types, and dropping and imputing missing values using measures of central tendency
* Exploratory Data Analysis (EDA), including computing summary statistics, computing percentage of sub categories of each categorical variable, plotting histogram, plotting boxplot, and plotting correlation matrix
* Feature Engineering, including regrouping subcategories within some categorical variables
* Dimensionality Reduction, including computing mutual information and implementing TruncatedSVD
* Model Building, including converting categorical variables to dummy variables, and building a predictive model using Random Forest Regressor
* Model Evaluation, including testing the model on test dataset
* Model Tuning, including implementing grid search to tune the model

## Technologies
* Python (Numpy, Pandas, Seaborn, Scikit-learn) 
* Google Colaboratory
* Microsoft Excel
* Microsoft PowerPoint

## Results and Interpretations
<img width="1076" alt="image" src="https://user-images.githubusercontent.com/98556651/236644735-4e5ee615-0a43-4e20-8522-a45c634baed4.png">
The model suggested that the age of the worker at the time of the accident, the number of years the worker has worked in the construction industry, and the municipality where the construction site is located are the top three factors that contribute to the injuries in the construction industry in Ontario. 

<img width="609" alt="image" src="https://user-images.githubusercontent.com/98556651/236644900-80bb92af-9377-4feb-9a18-9a8f4ca831f0.png">
Further investigation suggested that as the accident age range increases, the average year-to-date accident cost increases.

<img width="647" alt="image" src="https://user-images.githubusercontent.com/98556651/236646401-825a3fc6-ca2b-4770-ac24-167a43e651e9.png">
The analysis also showed that employees with less than 6 months of experience at the time of the accident contribute to around 62.73% of the total year-to-date accident costs.

This project is a part of the course [APS490: Multi-Disciplinary Capstone Design](https://engineering.calendar.utoronto.ca/course/aps490y1) under the [Department of Mechanical and Industrial Engineering](https://www.mie.utoronto.ca/) at the [University of Toronto.](https://www.utoronto.ca/)
