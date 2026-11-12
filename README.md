# Student Exam Score Predictor

## 📌 Overview
This project predicts student exam scores based on study habits and lifestyle factors. It demonstrates the end-to-end ML workflow: data preprocessing, feature engineering, model training, evaluation, visualization, and hyperparameter tuning.

## 🎯 Features
- Multiple Linear Regression model
- Feature scaling with scikit-learn pipelines
- Hyperparameter tuning using GridSearchCV (Linear, Ridge, Lasso)
- Dual visualizations: test set vs full dataset predictions
- Clean, reproducible workflow with requirements.txt

## 📂 Dataset
Synthetic dataset with 1000 rows, including:
- Hours Studied
- Attendance (%)
- Sleep Hours
- Assignments Completed
- Exam Score (Target)

## 🛠️ Tech Stack
- Python, Pandas, NumPy, scikit-learn, Matplotlib
- Jupyter Notebook in VS Code
- Git + GitHub

## ⚙️ Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/rajeshatmakuri17/ML-Student_score_predictor.git
   cd ML-Student_score_predictor
   ```
2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate
   ```
   On Windows:
   ```bash
   venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open and run `student_score_predictor.ipynb` in Jupyter Notebook or VS Code.

## 📊 Results
- MAE: ~2–5
- R² Score: ~0.9

## 💼 Resume Value
- End-to-end ML workflow
- Pipelines, scaling, hyperparameter tuning
- Production-style beginner project

## 🚀 Future Improvements
- Deploy with FastAPI + Docker
- Add MLflow experiment tracking
- Expand dataset with real-world data

## 📈 Visualizations
- Test Set Predictions (200 points)
- Full Dataset Predictions (1000 points)

## 🔑 Key Takeaways
Strong portfolio project demonstrating ML workflow, tuning, and visualization.
