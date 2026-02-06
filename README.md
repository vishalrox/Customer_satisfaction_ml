# Customer Satisfaction Prediction using Machine Learning

## 📌 Project Overview
Customer satisfaction plays a crucial role in evaluating the quality of support services. This project focuses on building a **machine learning model** to predict customer satisfaction ratings using historical customer support ticket data.

The aim is to understand how operational factors such as response time, resolution time, ticket type, and customer characteristics influence overall satisfaction.

---

## 📂 Dataset Description
The dataset consists of customer support tickets related to various technology products. Each record contains:

- Customer demographics (Age, Gender)  
- Product purchased  
- Ticket type, subject, and description  
- Ticket priority and communication channel  
- Response and resolution timestamps  
- Final **Customer Satisfaction Rating (1–5)** ⭐  

This dataset enables analysis in **customer behavior modeling, service optimization, and predictive analytics**.

---

## 🛠 Technologies Used

| Category | Tools |
|----------|------|
| Programming | Python |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Environment | VS Code, Jupyter Notebook |

---

## 🔄 Project Workflow

### 1️⃣ Data Preprocessing
- Removed non-informative columns (ID, Name, Email)  
- Handled missing values and filtered completed tickets  
- Converted timestamps into usable features  
- Engineered performance metrics:
  - **Response Time (hrs)**
  - **Resolution Time (hrs)**  

---

### 2️⃣ Exploratory Data Analysis (EDA)
Comprehensive analysis was performed to uncover patterns in support operations:

- Distribution of customer satisfaction ratings  
- Customer demographic trends  
- Ticket type, priority, and channel analysis  
- Monthly ticket trends  
- Most frequent customer issues  
- Relationship between resolution time and satisfaction  
- Feature correlations and customer segmentation  

---

### 3️⃣ Feature Engineering
- Defined feature matrix **X** and target **y**  
- Combined textual ticket information into a single feature  
- Encoded categorical variables  
- Removed datetime fields not suitable for modeling  
- Split data into **training and testing sets**

---

### 4️⃣ Feature Scaling
Standardized numerical features using **StandardScaler** to ensure consistent model performance.

---

### 5️⃣ Model Building
A **Random Forest Classifier** was trained to predict customer satisfaction levels.

---

### 6️⃣ Model Evaluation

Instead of focusing only on overall accuracy, the evaluation emphasizes **feature influence and model behavior**, which are more meaningful for service analytics.

**Key insights from the model:**

- ⏱ **Response Time** and **Resolution Time** are the strongest predictors of satisfaction  
- 📝 Ticket descriptions (text data) contain valuable signals  
- 👤 Customer demographics and product type have moderate influence  

The model provides a **baseline predictive framework** and highlights that customer satisfaction is influenced by multiple subtle factors rather than a single dominant variable.

---

## 📊 Business Insights
- Faster response and resolution times are strongly linked to higher satisfaction  
- Certain products generate more dissatisfaction, indicating areas for product improvement  
- Text-based complaints carry rich information for future NLP-driven analysis  

---

## 🚀 Future Improvements
To enhance predictive performance and business value:

- Apply **advanced NLP techniques** (TF-IDF, sentiment analysis)  
- Experiment with **boosting algorithms (XGBoost, LightGBM)**  
- Group satisfaction into broader categories (Low / Medium / High)  
- Perform hyperparameter tuning  

---

## 📁 Project Structure
```
Customer_satisfaction_ml.ipynb   # Main ML project notebook
customer_support_tickets.csv     # Dataset
README.md                        # Documentation
```

## Install Required Libraries
```
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Run the notebook in Jupyter or VS Code:
```
jupyter notebook Customer_satisfaction_ml.ipynb
```

## 🎓 Conclusion

This project demonstrates a complete end-to-end machine learning pipeline for analyzing and predicting customer satisfaction. While satisfaction prediction is inherently complex, the model successfully identifies key operational drivers and provides a foundation for data-driven service improvements.

# 👤 Author

Vishal Mehta
Machine Learning & Data Science Enthusiast
