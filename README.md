# Fitness & Lifestyle Prediction Using Machine Learning

This project uses machine learning to predict an individual's fitness and lifestyle health category based on input features like activity level, dietary preferences, daily steps, calories, and more. It includes preprocessing, feature engineering, EDA, and classification model development.

##  Problem Statement

The goal is to classify individuals as "healthy" or "unhealthy" based on daily habits, physical activity, diet, and physiological indicators using a supervised machine learning model.

##  Dataset

- Custom dataset: `innovize_final_ml.csv`
- Features include: 
  - Gender
  - Daily average steps
  - Daily calorie intake
  - Physical fitness score
  - Diet preference
  - Activity level
  - Sleep duration
  - Label: `is_healthy`

##  Features

- Exploratory Data Analysis (EDA)
- Missing value imputation using statistical and probabilistic sampling
- Feature visualization using Seaborn
- Data preprocessing and encoding
- Binary classification (Healthy vs. Unhealthy)
- Model training and accuracy evaluation

## Tech Stack

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- scikit-learn
- mlxtend (for decision region plotting)

##  How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/fitness-lifestyle-prediction.git
cd fitness-lifestyle-prediction
