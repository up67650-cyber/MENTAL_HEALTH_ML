🧠 Mental Health Prediction Using Machine Learning

A machine learning project that applies classification algorithms to predict mental health-related outcomes from input data. The project explores multiple models and hyperparameter tuning to improve predictive performance.

🚀 Features

- Implementation of Logistic Regression for classification.
- Random Forest classifier for capturing complex patterns in data.
- Hyperparameter tuning to optimize Random Forest performance.
- Model evaluation and comparison.
- Model serialization using Joblib.
- FastAPI backend for serving predictions.

🛠️ Tech Stack

- Language: Python
- Data Processing: Pandas, NumPy
- Machine Learning: Scikit-learn
- Algorithms: Logistic Regression, Random Forest
- Model Optimization: Hyperparameter Tuning
- Model Serialization: Joblib
- Backend API: FastAPI
- API Server: Uvicorn

⚙️ Machine Learning Workflow

1. Data Preparation: Load and prepare the dataset for training.
2. Preprocessing: Prepare input features and target labels.
3. Model Training: Train Logistic Regression and Random Forest classifiers.
4. Hyperparameter Tuning: Search for suitable Random Forest hyperparameters to improve model performance.
5. Model Evaluation: Compare models using appropriate classification metrics.
6. Model Saving: Save the selected trained model using Joblib.
7. API Integration: Load the saved model in FastAPI to generate predictions.

🌲 Algorithms Used

1. Logistic Regression

A classification algorithm used as a baseline model to estimate the probability of a target class.

2. Random Forest

An ensemble learning algorithm that combines multiple decision trees to make predictions and capture nonlinear relationships.

3. Hyperparameter Tuning

A model optimization process used to identify better Random Forest settings, potentially including the number of trees, maximum tree depth, and minimum samples required for splitting or creating a leaf.

📊 Model Evaluation

Model performance can be evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Add your actual evaluation results here once verified.

⚠️ Disclaimer

This project is intended for educational and research purposes. Predictions are not a medical diagnosis and should not replace professional mental health assessment.

👨‍💻 Author

Utkarsh Pandey

GitHub: "@up67650-cyber" (https://github.com/up67650-cyber)