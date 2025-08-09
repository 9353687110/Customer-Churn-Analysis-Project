# Customer Churn Analysis

## Project Overview
This project aims to predict customer churn — identifying customers who are likely to leave a company — using machine learning techniques. The dataset includes historical customer information, and the goal is to build a model that helps businesses improve customer retention.

## Features
- Data cleaning and preprocessing
- Feature engineering and selection
- Scaling of features using StandardScaler
- Model building using Random Forest Classifier
- Model evaluation with accuracy, precision, recall, and AUC-ROC

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn (for visualization)

## How to Run
1. Clone the repository  
   `git clone https://github.com/yourusername/customer-churn-analysis.git`  
2. Install required libraries  
   `pip install -r requirements.txt`  
3. Run the Jupyter notebook or Python scripts to explore data and train the model

## Results

- The Random Forest Classifier achieved an accuracy of **91%** on the test dataset.  
- Precision and recall scores indicate the model performs well in correctly identifying churned customers and minimizing false alarms.  
- The AUC-ROC score was **0.92**, showing good model discrimination between customers who churn and those who stay.  
- Feature importance analysis highlighted key factors influencing churn, such as tenure, monthly charges, and contract type.  
- The model helps the business proactively identify high-risk customers to improve retention strategies.  
