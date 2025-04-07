# 🫀 Heart Disease Classification

This project is a machine learning-based approach to predict whether a person has heart disease based on several clinical features.

## 📁 Project Structure

- `heart-disease-classification.ipynb`: Main Jupyter Notebook containing data preprocessing, model training, evaluation, and visualization.
- `README.md`: Project overview and setup instructions.

## 📊 Dataset

The dataset used in this project includes features such as:

- Age
- Sex
- Chest pain type
- Resting blood pressure
- Serum cholesterol
- Fasting blood sugar
- Resting ECG results
- Maximum heart rate achieved
- Exercise-induced angina
- ST depression
- Slope of peak exercise ST segment
- Number of major vessels
- Thalassemia
- **Target**: Presence of heart disease (1 = yes, 0 = no)

## ⚙️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## 🧠 Machine Learning Models

- Logistic Regression
- GridSearchCV for hyperparameter tuning
- ROC Curve and AUC score for evaluation

## 📈 Evaluation

The ROC Curve was used to visualize model performance. The best model was selected based on ROC AUC scores.
