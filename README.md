# Predicting-Rain-Fall-Using-Decision-Trees


🌧️ Predicting Rainfall Using Decision Trees
This project applies a Decision Tree Classifier to predict whether it will rain tomorrow in Australia, using meteorological data from the previous day. It's part of a series of experiments exploring different machine learning models on the same dataset to understand their tradeoffs in performance, interpretability, and deployment readiness.

📦 Dataset
Source: Kaggle – Rain in Australia Dataset

Records: ~142,000 rows

Target variable: RainTomorrow (Yes/No)

Features: Includes temperature, humidity, wind direction, pressure, and other meteorological readings

🧠 What This Project Covers
Exploratory Data Analysis (EDA)

Handling missing values and categorical variables

Splitting data into training and test sets

Building a Decision Tree Classifier using scikit-learn

Visualizing the structure of the tree

Evaluating model performance with accuracy and classification reports

Understanding feature importance and overfitting risks

📊 Why Decision Trees?
Decision Trees offer:

High interpretability

Flexibility with mixed data types

No need for feature scaling

Easy visualization and business explanation

In this project, Decision Trees are compared conceptually to logistic regression to better understand model strengths and limitations.

⚙️ Tools & Libraries
Python

Pandas

NumPy

Matplotlib & Seaborn

Scikit-learn

Google Colab

📈 Model Performance
The model was evaluated using:

Accuracy score

Confusion matrix



📌 Note: As with most classification tasks involving imbalanced classes, accuracy alone is not enough — hence the inclusion of more robust classification metrics.

🧠 Key Learnings
How tree depth and branching affect overfitting

The trade-off between model complexity and generalization

Importance of feature selection and preprocessing in decision trees

Visualizing decision trees for explainability

🚀 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/Sherrif-Isam/Predicting-Rain-Fall-Using-Decision-Trees.git
Open the notebook: Australia_Rain_Decision_Trees.ipynb

Run the cells in order using Google Colab or Jupyter Notebook.

📌 Author
Sherrif Isam
GitHub: @Sherrif-Isam

