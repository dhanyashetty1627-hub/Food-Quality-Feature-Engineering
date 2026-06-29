# Food-Quality-Feature-Engineering


## 📌 Project Overview

This project was completed as part of the **Week 3 Internship Task: Feature Engineering and Exploratory Modeling**. The objective is to improve the predictive capability of the Zomato Restaurant Dataset by creating meaningful features, transforming existing data, and outlining exploratory machine learning models.

Feature engineering is an important step in data science because it converts raw data into more informative variables that improve model performance and provide deeper business insights.

---

# 🎯 Objectives

- Analyze existing features in the dataset
- Create meaningful new features
- Transform categorical and numerical data
- Explore relationships among variables
- Prepare the dataset for predictive modeling
- Develop an exploratory modeling strategy

---

# 📂 Dataset

**Dataset Used:** Zomato Restaurant Dataset

The dataset contains restaurant-related information such as:

- Restaurant Name
- Location
- Cuisines
- Restaurant Rating
- Votes
- Approximate Cost for Two
- Online Order Availability
- Table Booking Availability

---

# ⚙️ Feature Engineering Performed

The following engineered features were created:

### 🍽️ Cuisine Count
Calculated the number of cuisines offered by each restaurant.

### 💰 Cost Category
Converted restaurant cost into:
- Low
- Medium
- High

### ⭐ Popularity Score
Created using:

Popularity Score = Rating × Votes

### 🌐 Online Presence
Combined:
- Online Order
- Table Booking

to represent restaurant online availability.

### 📍 Location Popularity
Calculated the average restaurant rating for each location.

---

# 🔄 Feature Transformation

The following preprocessing and transformation techniques were applied:

- Label Encoding
- One-Hot Encoding
- Feature Scaling
- Data Type Conversion

---

# 📊 Exploratory Modeling

The project proposes the following machine learning models for future analysis:

- Linear Regression
- Decision Tree
- Random Forest
- K-Means Clustering

---

# ✅ Validation Strategy

The engineered features can be evaluated using:

- Correlation Analysis
- Feature Importance
- Train-Test Split
- Cross Validation
- Model Performance Comparison

---

# 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# 📁 Repository Contents

```
📂 Zomato-Feature-Engineering-and-Exploratory-Modeling

│── Feature_Engineering_and_Exploratory_Modeling.ipynb
│── processed_zomato_dataset.csv
│── zomato_feature_engineered.csv
│── Week3_Project_Report.pdf
│── README.md
```

---

# 📈 Expected Outcome

This project demonstrates how feature engineering improves dataset quality by creating meaningful variables that enhance exploratory analysis and prepare data for predictive machine learning models.

---

# 👩‍💻 Author

**Dhanya Dinesh Shetty**

AI & DS Engineering Student

A. C. Patil College of Engineering

Internship: **Yuva Intern**
