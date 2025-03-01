🚀 Insurance Claim Prediction

This project applies machine learning techniques to predict insurance charges and the likelihood of filing a claim based on key features like BMI, smoker status, and age. It also includes K-Means clustering to segment risk groups for insurance pricing optimization.

🔍 Key Features
✔ Predicts Insurance Charges using Random Forest Regression
✔ Performs Clustering (K-Means) on BMI & Charges to segment risk groups
✔ Elbow Method to determine the optimal number of clusters
✔ Tkinter GUI for real-time predictions

📊 Machine Learning Models Used
RandomForestRegressor & Linear Regression Comparison-> Predicts insurance charges
Statistical Test: Shapiro Normality,Mann- Whitney U test
K-Means Clustering -> Segments policyholders into risk groups

## Installation

### Clone the Repository
git clone https://github.com/Beena-Kurian/Insurance_Claim_Prediction.git
cd Insurance-Claim-Prediction

### Usage
* Run Jupyter Notebook
* jupyter notebook
* Open Insurance_Claim_Prediction.ipynb and execute the cells

This launches a GUI where users can enter age, BMI, smoker status, and get predictions.

## Results & Insights

* Smoking significantly increases medical charges.
* K-Means clustering groups policyholders into different risk categories.
* Combining BMI & Smoking leads to better risk assessment.
