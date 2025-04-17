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

##  Model Performance

The Logistic Regression model achieved excellent performance:

- **Training Accuracy**: 99.52%
- **Testing Accuracy**: 99.42%
- **Overall Accuracy**: 99.42%
- **Macro F1-Score**: 0.99

  <img width="446" alt="image" src="https://github.com/user-attachments/assets/3cddd0e4-14c4-4bbb-9f99-f939080ccaec" />

##  Decision Boundary Visualization

This visualization shows how the logistic regression model classifies individuals based on **physical fitness** and **mindfulness** (both scaled). The shaded regions represent the model's decision boundary:

- Red Region: Predicted as Unhealthy (0)
- Blue Region: Predicted as Healthy (1)

<img width="847" alt="image" src="https://github.com/user-attachments/assets/fd3a48b8-502a-485a-9839-7b411316786b" />



##  How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/fitness-lifestyle-prediction.git
cd fitness-lifestyle-prediction
