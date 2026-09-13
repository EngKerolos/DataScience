### Demo Dataset 
The dataset contains 918 records with 12 anonymized features (Age, Sex, ChestPainType, RestingBP, Cholesterol, FastingBS, RestingECG, MaxHR, ExerciseAngina, Oldpeak, ST_Slope, HeartDisease).  
It is anonymized and does not include personally identifiable information (PII).  

# DataScience
Heart Disease Prediction using SVM

# Heart Disease Prediction

A machine learning project that predicts heart disease risk using a Support Vector Machine (SVM) classifier. Built with Python, Pandas, and Scikit-Learn.

## Description

This project builds an end-to-end ML pipeline to classify whether a patient is at risk of heart disease based on clinical features. It includes exploratory data analysis (EDA), feature engineering, model training, and evaluation.

The model achieved **87.5% accuracy** on the test set.

## Dataset

The dataset contains **918 records** with 12 clinical features:

| Feature | Description |
|---|---|
| Age | Patient age |
| Sex | Gender |
| ChestPainType | Type of chest pain |
| RestingBP | Resting blood pressure |
| Cholesterol | Serum cholesterol |
| FastingBS | Fasting blood sugar |
| RestingECG | Resting ECG results |
| MaxHR | Maximum heart rate |
| ExerciseAngina | Exercise-induced angina |
| Oldpeak | ST depression |
| ST_Slope | Slope of peak exercise ST segment |
| HeartDisease | Target (0 = No, 1 = Yes) |

The dataset is anonymized and contains no personally identifiable information (PII).

## Project Structure

DataScience/
├── DataScience.ipynb  # Full ML pipeline notebook
└── heart.csv          # Dataset


## How to Run


# 1. Clone the repository
git clone https://github.com/EngKerolos/DataScience
cd DataScience

# 2. Install dependencies
pip install pandas numpy matplotlib scikit-learn jupyter

# 3. Launch the notebook
jupyter notebook DataScience.ipynb


## Pipeline

1. **Data Loading** — Load and inspect the dataset
2. **EDA** — Explore distributions, correlations, and class balance
3. **Feature Engineering** — Encode categorical variables, scale features
4. **Model Training** — Train an SVM classifier
5. **Evaluation** — Accuracy, confusion matrix, classification report

## Results

| Metric | Score |
|---|---|
| Accuracy | 87.5% |
| Model | SVM (Support Vector Machine) |

## Tech Stack

- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Scikit-Learn
- **Environment:** Jupyter Notebook

## License

MIT
