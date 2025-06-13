
#  Enhanced Salary Prediction System using Random Forest

This project predicts employee salaries based on various features using Machine Learning. It utilizes **Random Forest**, a powerful ensemble algorithm, along with categorical encoding for accurate predictions.

---

##  Project Files

- `salary_prediction.ipynb` – Main Jupyter notebook
- `salaries.csv` – Dataset used
- `requirements.txt` – List of Python dependencies

---

##  Dataset Overview

The dataset includes:

- **Education Level**
- **Job Title**
- **Years of Experience**
- **Location**
- **Industry**
- **Salary** (Target)

All categorical variables are encoded appropriately for model training.

---

## Technologies Used

- Python 
- Pandas
- NumPy
- Scikit-learn
- Seaborn & Matplotlib

---

##  ML Workflow

1. Load and explore dataset
2. Clean missing values and encode categorical features
3. Train a Random Forest Regressor model
4. Evaluate model using R² Score, MAE, RMSE
5. Visualize feature importances and results

---

##  Sample Results

- Model: `RandomForestRegressor`
- Accuracy (R² Score): ~85–90%
- Visual outputs:
  - Feature importance chart
  - Predicted vs Actual salaries

---

##  How to Run

1. **Clone the repo**:
   ```bash
   git clone https://github.com/your-username/salary-prediction-project.git
   cd salary-prediction-project
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch the notebook**:
   Open `salary_prediction.ipynb` in Jupyter or VS Code and run all cells.

---

##  Future Improvements

- Add more ML models (Linear, XGBoost, etc.)
- Deploy as a web app (Flask or Streamlit)
- Perform hyperparameter tuning
- Handle outliers and feature scaling

---

##  Author

**Faiz Azam**  
BS Artificial Intelligence  
Sindh Madressatul Islam University  
Email: faiyz.azam@gmail.com  


---

##  Tags

`#MachineLearning` `#Python` `#RandomForest` `#DataScience` `#AIProjects`
