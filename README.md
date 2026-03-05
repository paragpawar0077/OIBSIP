# 🌸 OIBSIP – Data Science Internship Projects

This repository contains the projects completed as part of the **Oasis Infobyte Data Science Internship Program (OIBSIP)**.

Each task demonstrates practical implementation of Data Science and Machine Learning concepts including:

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Model Building
* Model Evaluation
* Data Visualization

---

## 📂 Repository Structure



```
OIBSIP/
│
├── TASK_1/
│   ├── iris_Task1.ipynb
│   ├── Iris.csv
│
├── TASK_2/
│   ├── TASK2.ipynb
│   ├── Unemployment in India.csv
│
├── TASK_3/
│ ├──Task3_Car_Price_Prediction.ipynb
│ ├── car data.csv
│
├── TASK_4/
│ ├── spam_detection.ipynb
│ ├── spam.csv
│
├── TASK_5/
│ ├── sales_prediction.ipynb
│ ├── Advertising.csv
---



 ✅ TASK 1: Iris Flower Classification

📌 Objective

To build a Machine Learning model that classifies iris flowers into three species:

* Setosa
* Versicolor
* Virginica

based on sepal and petal measurements.

## 🧠 Approach

* Data Exploration
* Data Preprocessing
* Train-Test Split (Stratified)
* Logistic Regression Model
* Model Evaluation using Accuracy Score & Classification Report

## 📈 Result

The model achieved high accuracy and successfully classified all three species.

---

# ✅ TASK 2: Unemployment Analysis with Python

## 📌 Objective

To analyze unemployment trends in India and understand the impact of COVID-19 using data visualization and exploratory data analysis techniques.

## 🧠 Approach

* Data Cleaning
* Date Conversion & Feature Extraction
* Time-Series Analysis
* State-wise Comparison
* Rural vs Urban Analysis
* Visualization using Matplotlib

## 📈 Key Insights

* Sharp rise in unemployment during 2020 (COVID-19 impact).
* State-wise variations observed.
* Rural and Urban employment trends differed significantly.

---

# ✅ TASK 3: Car Price Prediction (Regression Problem)

## 📌 Objective

To build a Machine Learning model that predicts the selling price of used cars based on various features.

## 📊 Dataset Features

* Year
* Present Price
* Driven Kilometers
* Fuel Type
* Transmission
* Owner
* Selling Price (Target Variable)

## 🧠 Approach

* Data Cleaning & Preprocessing
* Feature Engineering (Car Age creation)
* Correlation Analysis
* Encoding Categorical Variables (One-Hot Encoding)
* Train-Test Split
* Model Training & Comparison

## 🤖 Models Used

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

## 📈 Results

| Model | R² Score |
|------|------|
| Linear Regression | ~0.59 |
| Decision Tree | ~0.95 |
| Random Forest | ~0.96 |

Random Forest performed best due to its ability to capture non-linear relationships and reduce overfitting.

---

# ✅ TASK 4: Email Spam Detection (Classification Problem)

## 📌 Objective

To build a Machine Learning model that can classify SMS messages as **Spam** or **Ham (Not Spam)** using Natural Language Processing techniques.

## 📊 Dataset Features

* **Label** – Indicates whether the message is spam or ham
* **Message** – The actual SMS text content

## 🧠 Approach

* Data Cleaning & Preprocessing
* Text Normalization (Lowercasing, removing punctuation)
* Feature Extraction using **TF-IDF Vectorization**
* Train-Test Split
* Model Training & Evaluation

## 🤖 Models Used

* Multinomial Naive Bayes
* Logistic Regression

## 📈 Model Evaluation

Models were evaluated using:

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix

Naive Bayes performed particularly well for this task because it is highly effective for **text classification problems involving word frequencies**.

---

# ✅ TASK 5: Sales Prediction Using Python

## 📌 Objective

To build a Machine Learning model that predicts product sales based on advertising expenditures across different media platforms.

## 📊 Dataset Features

* **TV Advertising Budget**
* **Radio Advertising Budget**
* **Newspaper Advertising Budget**
* **Sales (Target Variable)**

## 🧠 Approach

* Data Exploration & Cleaning
* Exploratory Data Analysis (EDA)
* Correlation Analysis
* Train-Test Split
* Model Training
* Model Evaluation

## 🤖 Models Used

* Linear Regression
* Random Forest Regressor

## 📈 Results

The models were evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score

TV advertising showed the strongest correlation with sales, indicating that TV promotions had the greatest impact on product sales.

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook
* Natural Language Processing (NLP)

---

## 🚀 Future Improvements

* Hyperparameter Tuning
* Cross-Validation
* Model Deployment (Web App)
* Deep Learning based text classification

---

## 👨‍💻 Author

**Parag Pawar**  
Data Science Intern – Oasis Infobyte

⭐ If you found this repository helpful, feel free to star it!

