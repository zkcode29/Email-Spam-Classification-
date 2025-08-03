#  Email Spam Classification - NLP & Machine Learning Project

A complete machine learning pipeline to classify emails as **Spam** or **Ham** using advanced Natural Language Processing (NLP) techniques and classification algorithms.


---

##  Project Objective

The goal of this project is to develop an accurate machine learning model to classify email messages as either **legitimate ("Ham")** or **unsolicited ("Spam")**. This involves:

- Cleaning and preprocessing raw text data
- Extracting meaningful features
- Building and tuning multiple machine learning models
- Evaluating and visualizing model performance

---

##  Key Features

-  **Exploratory Data Analysis (EDA)**
-  **Text Cleaning & Preprocessing (NLTK)**
-  **Feature Engineering**
-  **Machine Learning Pipelines**
-  **GridSearchCV for Hyperparameter Tuning**
-  **Evaluation Metrics: Accuracy, Precision, Recall, F1, Confusion Matrix**
-  **Visualizations: ROC Curve, Confusion Matrix Heatmap**

---

##  Tools & Libraries

- Python 3.x
- Pandas
- Numpy
- Scikit-learn
- NLTK
- Plotly
- Matplotlib & Seaborn

---

| Step | Stage                               | Description                                                                                     |
| ---- | ----------------------------------- | ----------------------------------------------------------------------------------------------- |
| 1    | Data Loading                        | Load the dataset (`spam_dataset.csv`) using `pandas.read_csv()`                                 |
| 2    | EDA & Visualization                 | Explore data structure, missing values, and class distribution with visual tools                |
| 3    | Preprocessing & Feature Engineering | Clean text (remove noise, lowercase, stopwords), and create features (length, word count, etc.) |
| 4    | Model Training & Tuning             | Use `Pipeline` + `GridSearchCV` with models like Logistic Regression, SVM, and Random Forest    |
| 5    | Model Evaluation                    | Assess metrics: Accuracy, Precision, Recall, F1-Score, Confusion Matrix, ROC                    |
| 6    | Model Deployment                    | Deploy final model using Streamlit to create a real-time spam detection web app                 |



## Author
Izaz khan|Artificial Intelligence 


