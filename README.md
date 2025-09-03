🚢 Titanic Survival Prediction

Predicting passenger survival from the Titanic dataset using machine learning. This project demonstrates an end-to-end ML workflow including data preprocessing, EDA, feature engineering, model testing, and prediction.

📊 Project Workflow
1. Importing Libraries

pandas, numpy → data handling & numerical computation

matplotlib, seaborn → data visualization

2. Data Loading

Loaded train & test datasets with pandas.

Prepared data for analysis and model building.

3. Exploratory Data Analysis (EDA)

Visualized feature distributions (Age, Fare, SibSp, Parch).

Explored survival patterns based on gender, class, and family size.

Identified correlations and outliers.

4. Data Cleaning & Feature Engineering

Imputed missing values.

Dropped irrelevant features (PassengerId, Name, Ticket, Cabin).

Engineered new features to improve predictions.

5. Model Testing

Tested multiple ML algorithms:

✅ Logistic Regression

✅ Decision Tree

✅ Random Forest

✅ Extra Trees

✅ XGBoost

✅ LightGBM

Best Accuracy: 73.8% 🎯

6. Prediction & Submission

Applied the final model on the test set.

Generated a submission file (CSV) for evaluation (Kaggle-style).

📌 Results & Insights

Passenger gender, class, and age had the strongest influence on survival.

Ensemble models (RandomForest, XGBoost, LightGBM) outperformed simpler models.

Final accuracy: 73.8%.

🛠️ Tech Stack

Python 🐍

Pandas | NumPy

Matplotlib | Seaborn

Scikit-learn

XGBoost | LightGBM

🚀 How to Run
# Clone repo
git clone https://github.com/your-username/titanic-survival-prediction.git

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook Titanic_Survival_Prediction.ipynb

🎯 Conclusion

This project highlights the practical use of ML in predictive analytics and demonstrates the importance of data cleaning, feature engineering, and model selection.
