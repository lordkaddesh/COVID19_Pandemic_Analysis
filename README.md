

COVID-19 Pandemic Analysis and Forecasting

Project Overview

This project provides an in-depth analysis and forecasting of the COVID-19 pandemic using data science techniques. The focus is on understanding the spread, recovery rates, and predictive trends of the disease to aid in public health decision-making. It includes detailed visualizations, exploratory data analysis (EDA), and machine learning models to forecast future case trends.


Key Features

1. Exploratory Data Analysis (EDA):

Trends in COVID-19 cases for the top 10 affected countries.

Death and recovery rates analysis.

Correlation heatmap of confirmed, deaths, recovered, and active cases.


2. Predictive Modeling:

Built a Random Forest regression model to forecast the number of confirmed cases.

Achieved a low Mean Absolute Error (MAE) for accuracy.


3. Visualizations:

Line charts for COVID-19 trends over time.

Boxplots for death and recovery rates across countries.

Heatmap to show correlations between key metrics.


4. Actionable Insights:

Insights on recovery and death rates based on early interventions.

Resource allocation recommendations for public health agencies.


How to Run the Project

1. Dataset:

Download the dataset (covid_19_clean_complete.csv) from Johns Hopkins University COVID-19 Data Repository or similar sources.

Place the dataset in the same directory as the Python script.



2. Setup:

Install required Python libraries:

pip install numpy pandas matplotlib seaborn scikit-learn

Run the covid19_analysis.py script in your Python environment (Jupyter Notebook, VS Code, etc.).


3. Output:

Visualizations and model outputs will be saved as PNG files in the project directory.

Insights and metrics will be displayed in the console.

Project Structure

covid19_analysis.py: Python script containing the data preprocessing, EDA, modeling, and visualization code.

covid_19_clean_complete.csv: Placeholder for the COVID-19 dataset (replace with the actual data).

Generated PNG files:

top_countries_trend.png

correlation_heatmap.png

actual_vs_predicted.png

Insights

1. Top Countries: COVID-19 cases peaked differently across countries, with some having early recovery phases due to strict interventions.


2. Correlation Findings: Death and recovery rates are inversely related, emphasizing the importance of timely healthcare access.


3. Predictive Modeling: Random Forest Regression achieved a reliable forecast for confirmed cases, helping in better resource planning.

Dataset Source

The dataset used in this project can be downloaded from the Johns Hopkins University GitHub repository.


Acknowledgments

Data sourced from publicly available repositories maintained by Johns Hopkins University.

Libraries: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn.



