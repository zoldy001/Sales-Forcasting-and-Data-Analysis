# Sales Forcasting - Rossmann Store

This project focuses on predicting future sales for Rossmann Stores using historical sales data. The dataset comprises historical sales data for 1,115 Rossmann stores, including additional contextual information such as promotions, holidays, and competition. TWe will use this data to build a robust forecasting model that provides accurate predictions of future 
sales allowing optimisations of resource allocation and operational planning.

The project is structured as follows:

* Exploratory Data Analysis (EDA): Uncover patterns and identify key factors that influence sales performance.
* Model Development and Optimization: Train and fine-tune machine learning models to accurately forecast future sales.
* Business Recommendations: Translate insights into practical strategies to improve sales outcomes.

#### How to View This Project  
The analysis is presented in a Jupyter Notebook. To view it: Open the notebook directly on GitHub (.ipynb file). 

## Tools and Libraries Used 

- **Python Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Sklearn
- **Models:** Linear Regression, XGBoost, Prophet
- **Environment:** Kaggle Notebook
  
This project utilized various Python libraries to handle data analysis and visualization efficiently. Pandas and NumPy were used for data manipulation and numerical computations, while Matplotlib and Seaborn helped create insightful visualizations. We will be using machine learning models **Linear Regression** and **XGBoost,** for predictive analysis, and **Prophet** was used for *time-series* forecasting, we will then compare the performance of these models and determine which provides the most accurate sales predictions.. All analysis was conducted in a Kaggle Notebook.

## Dataset

## Exploratory Data Analysis (EDA)

1.	Impact of Holidays on Sales:
	•	Easter holidays generate the highest daily sales, followed by public holidays and Christmas.
	•	School holidays have a minor positive effect.
	2.	Store Type and Assortment Influence:
	•	Store type ‘b’ significantly outperforms others, with nearly 50% higher sales.
	•	Stores with extra assortment generate the highest sales, indicating that a wider product range boosts performance.
	3.	Promotions and Sales Variability:
	•	Sales during promotional periods are nearly double (median: 7,000–8,000) compared to non-promotional periods (median: 4,000–5,000).
	•	Promotions lead to more consistent sales with less variance.
	4.	Proximity to Competition:
	•	Stores closer to competitors tend to perform slightly better, likely due to higher population density in these areas.
	5.	Seasonality in Sales:
	•	Monthly sales peak in January (around 8,500 units) and show an overall upward trend.
	•	Fluctuations suggest seasonality, with occasional dips in October-November, likely influenced by promotions or post-holiday effects.
	6.	Weekly Sales Patterns:
	•	Sales peak at the beginning of the week and taper off, with dramatic drops on Sundays when most stores are closed.
