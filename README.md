# Titanic-Survival-Prediction

A machine learning project to predict passenger survival on the Titanic using classification algorithms. This project analyzes historical data to identify key factors that influenced survival rates.

## 📊 Dataset
- **Source:** Kaggle Titanic - Machine Learning from Disaster competition
- **Records:** 891 passengers in training set, 418 in test set
- **Features:** 12 attributes including Age, Sex, Pclass, Fare, SibSp, Parch, Embarked

## 🛠️ Technologies Used
- **Language:** Python 3.x
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Algorithm:** Random Forest Classifier
- **Tools:** Jupyter Notebook

## 🔍 Implementation Workflow
1. **Data Preprocessing:** Handled missing values in Age and Embarked columns using median and mode
2. **Feature Engineering:** Created new features like FamilySize and extracted Titles from names
3. **Exploratory Data Analysis:** Visualized survival rates by Gender, Pclass, and Age groups
4. **Model Training:** Trained Random Forest with 100 estimators using 80-20 train-test split
5. **Model Evaluation:** Measured performance using accuracy, precision, and confusion matrix

## 📈 Results
- **Accuracy Achieved:** 82.68% on validation data
- **Key Findings:** Sex, Pclass, and Age were the most important features for survival prediction
- **Model Performance:** Outperformed baseline Logistic Regression by 4.2%

## 🎯 Key Learnings
This project helped me understand the complete ML pipeline from data cleaning to model deployment. I learned how ensemble methods like Random Forest reduce overfitting and how feature importance helps in model interpretability.

## 🚀 Future Improvements
- Hyperparameter tuning using GridSearchCV
- Try XGBoost and compare performance
- Deploy model using Streamlit for real-time predictions

--------------------------------------------------------------------------
Author       : Dhivakar B  
Project for  : Amazon ML Summer School 2026
