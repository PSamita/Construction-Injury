# Injuries in Construction Industry: Exploring Causes of Accidents Using Machine Learning
This project is a part of the course [APS490: Multi-Disciplinary Capstone Design] (https://engineering.calendar.utoronto.ca/course/aps490y1) under the [Department of Mechanical and Industrial Engineering] (https://www.mie.utoronto.ca/) at the [University of Toronto.] (https://www.utoronto.ca/)

#### -- Project Status: [Completed]

## Project Objective
The purpose of this project is to develop a comprehensive data analysis service for the Infrastructure Health and Safety Association (IHSA) to identify leading factors contributing to injuries in the construction industry in Ontario. This service will assist the IHSA in making informed decisions on where to allocate resources to prevent or reduce injuries. 

### Partner
* Client: [The Infrastructure Health & Safety Association (IHSA)] (https://www.ihsa.ca/)
* Supervisor: [Professor Greg A. Jamieson] (https://www.mie.utoronto.ca/faculty_staff/jamieson/)

### Methods Used
* Data Cleaning, including filtering relevant data, correcting data types, and dropping and imputing missing values using measures of central tendency
* Exploratory Data Analysis (EDA), including computing summary statistics, computing percentage of sub categories of each categorical variable, plotting histogram, plotting boxplot, and plotting correlation matrix
* Feature Engineering, including regrouping subcategories within some categorical variables
* Dimensionality Reduction, including computing mutual information and implementing TruncatedSVD
* Model Building, including converting categorical variables to dummy variables, and building a predictive model using Random Forest Regressor
* Model Evaluation, including testing the model on test dataset
* Model Tuning, including implementing grid search to tune the model

### Technologies
* Python (Numpy, Pandas, Seaborn, Scikit-learn) 
* Google Colaboratory
* Microsoft Excel
* Microsoft PowerPoint

## Project Description
The IHSA has been using the dataset to keep track of the injuries and analyze the data accordingly. However, the injuries data are interpreted and reported based on their categories and no further data analysis into each injury type and cause are investigated. This project aims to provide the client with a service to suggest a data analysis process that implements a machine learning algorithm to analyze the dataset. The result from the analysis and the interpretation of the result, along with recommendations for the IHSA to optimize the utilization of the collected data, are included in this service. Although the IHSA covers a wide range of trade sectors, the client wants this project to focus only on the construction industry. 

After analyzing the dataset and brainstorming design alternative options, three design alternatives were proposed. Each design consists of data analysis, data visualization, data interpretation, and recommendations for the IHSA. The data analysis part, specifically a predictive model that is used to suggest the top leading factors, is what makes each design alternative differ from each other. Random Forest Regressor, Decision Tree Regressor, and Linear Regression were chosen as the best fit algorithm to build the model which can suggest the leading factors that affect the accident cost for this project. A detailed description and evaluation of the models was conducted, and the design that implemented Random Forest Regressor algorithm was chosen as the proposed design. The results from data analysis were used to plot graphs and charts to represent the data in a way that can be easily understood. Interpretation and explanation of each graphical representation was also provided to ensure readers’ accurate and concise data interpretation. Recommendations for improving the data collection, storage, and utilization were included in this report to suggest ways to optimize the usage of collected data.
