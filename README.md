📊 Employee Burnout Analysis with PCA & Regression Models
This project aims to analyze employee burnout using data visualization, preprocessing techniques, dimensionality reduction via PCA, and regression modeling. It is designed as an end-to-end machine learning pipeline for predicting the Burn Rate of employees.

🚀 Project Overview
Objective:
Predict employee Burn Rate using key features such as mental fatigue score, designation, gender, and company type.
Dataset:
The dataset used is employee_burnout_analysis-AI.csv and includes features like:
- Gender
- Designation
- Company Type
- Work From Home Setup
- Mental Fatigue Score
- Resource Allocation
- Burn Rate (Target variable)

🛠️ Technologies & Libraries Used
Python 3.x
Pandas, NumPy (Data handling)
Seaborn, Matplotlib, Plotly (Data visualization)
Scikit-learn (Modeling and preprocessing)
PCA (Dimensionality reduction)

📂 Project Structure
employee-burnout-analysis/
│
├── data/
│   └── employee_burnout_analysis-AI.csv
│
├── burnout_analysis.ipynb
│
└── README.md



📈 Workflow
1. Data Loading & Preprocessing
Null value treatment with mean imputation
Datatype conversion and duplicate removal
Skewness analysis and cleaning

2. Exploratory Data Analysis (EDA)
Count plots for Gender, WFH Setup, Company Type
Histograms of numerical features
Correlation heatmaps
Interactive Plotly visualizations for Burn Rate and Mental Fatigue Score

3. Label Encoding
Converted categorical columns to numerical using Label Encoding

4. Feature Selection & PCA
Selected key numerical features
Reduced dimensions using PCA (95% variance explained)

5. Model Training
Models used:
Random Forest Regressor
AdaBoost Regressor
Metrics:
R² Score (Training and Testing Accuracy)

📊 Results
Example output (you can update this with your actual results):

Model	            Training Accuracy	Testing Accuracy
Random Forest           93.45%	            87.12%
AdaBoost Regressor	    89.02%	            83.56%

📜 How to Run
Clone the repository or download the files.
Ensure the dataset is placed in a data/ folder.

Install dependencies:
pip3 install pandas numpy seaborn matplotlib plotly scikit-learn

📌 Author
Vishruth Shelkey
Feel free to connect for feedback or improvements!
