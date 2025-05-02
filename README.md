# IBM HR Attrition: Data Analysis & Predictive Modeling

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0%2B-orange)
![Pandas](https://img.shields.io/badge/Pandas-1.3%2B-brightgreen)

An end-to-end data science project analyzing employee attrition patterns and building a predictive model using IBM HR data.

## Key Insights
- 🚨 **Overtime employees have 3x higher attrition** (30.5% vs 10.4%)
- 📊 **Entry-level (JobLevel 1) most vulnerable** (40% attrition for overtime workers)
- ⚖️ **Work-life balance matters**: 89.6% retention for standard-schedule employees

## Model Performance
| Metric          | Score |
|-----------------|-------|
| Accuracy        | 81%   |
| Recall (Leavers)| 68%   |
| F1-Score        | 43%   |

## Tech Stack
- **Data Processing**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Modeling**: Scikit-learn (Random Forest)
- **Deployment**: Joblib (model serialization)

## Repository Structure
└── IBM-HR-Attrition/
    ├── 📂 data/
    │   ├── IBM_HR_Employee_Attrition.csv
    │   ├── processed_data.joblib
    │   └── training.joblib
    │
    ├── 📂 notebooks/
    │   ├── 1_Data_Cleaning.ipynb
    │   ├── 2_Exploratory_Analysis.ipynb
    │   └── 3_Model_Training.ipynb
    │
    ├── 📂 models/
    │   └── rf_model.joblib
    │
    ├── requirements.txt
    └── README.md
