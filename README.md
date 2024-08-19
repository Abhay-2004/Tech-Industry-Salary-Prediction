# Tech Industry Salary Prediction

## Overview
This project analyzes a dataset of tech industry salaries and develops machine learning models to predict salaries based on various factors such as experience level, job title, company size, and remote work ratio. The project encompasses data cleaning, exploratory data analysis (EDA), feature engineering, and the implementation of several machine learning algorithms.

## Dataset
The dataset (`salaries.csv`) contains information about tech industry salaries, including:
- Experience level
- Employment type
- Job title
- Salary in USD
- Company location
- Company size
- Remote work ratio

## Project Structure
1. Data Cleaning and Preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Model Development and Evaluation
5. Hyperparameter Tuning
6. Model Comparison

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Bokeh

## Key Findings
1. Salary distribution shows a right skew, which is expected in the industry.
2. Experience level and job title are the most influential factors in determining salary.
3. There's a correlation between company size and salary, with larger companies generally offering higher salaries.
4. Remote work ratio has some impact on salary, but the relationship is not straightforward.

## Machine Learning Models
We implemented and compared several regression models:
1. K-Nearest Neighbors (KNN) Regressor
2. Linear Regression
3. Random Forest Regressor
4. Gradient Boosting Regressor

The Random Forest and Gradient Boosting models performed the best, with the lowest Mean Absolute Error (MAE) and Mean Squared Error (MSE).

## Visualizations
The project includes various visualizations to aid in understanding the data and model performance:
- Salary distributions
- Boxplots of salary by experience level and company size
- Scatter plots of salary vs. remote work ratio
- Feature importance plots
- Model performance comparison charts

## Future Work
1. Collect more recent data to keep the model up-to-date with current market trends.
2. Incorporate more features such as specific skills or technologies used in each role.
3. Experiment with more advanced models like XGBoost or neural networks.
4. Develop a web application for easy salary prediction based on user input.

## How to Use
1. Clone the repository
2. Install the required dependencies: `pip install -r requirements.txt`
3. Run the Jupyter notebooks in order:
   - 01_Data_Cleaning.ipynb
   - 02_Exploratory_Data_Analysis.ipynb
   - 03_Feature_Engineering.ipynb
   - 04_Model_Development.ipynb
