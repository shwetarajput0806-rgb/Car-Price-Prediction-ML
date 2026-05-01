🚗 Ford Car Price Prediction - Notebook Explanation

📌 Overview

This notebook demonstrates the complete workflow of predicting Ford car prices using Machine Learning.
It includes data preprocessing, exploratory data analysis, feature engineering, model building, and evaluation.

---

📂 Dataset Description

The dataset contains information about used Ford cars with the following features:

- Model
- Year
- Transmission
- Mileage
- Fuel Type
- Engine Size
- Price (Target Variable)

---

🔍 Step-by-Step Process

1️⃣ Data Loading

- Imported dataset using Pandas
- Checked basic structure using ".head()", ".info()", ".describe()"

---

2️⃣ Data Cleaning

- Checked for missing values
- Removed/handled null values
- Verified data types

---

3️⃣ Exploratory Data Analysis (EDA)

- Visualized relationships using:
  - Histograms
  - Count plots
  - Heatmaps
- Identified important features affecting price

---

4️⃣ Feature Engineering

- Converted categorical variables into numerical form
- Applied:
  - Label Encoding
  - One Hot Encoding

---

5️⃣ Model Building

- Split data into training and testing sets
- Applied Linear Regression model

---

6️⃣ Model Evaluation

- Evaluated using R² Score

📊 Results:

- Label Encoding → R² Score: 0.73
- One Hot Encoding → R² Score: 0.84

✅ One Hot Encoding gave better performance.

---

📈 Key Insights

- Car price is influenced by year, mileage, and engine size
- Encoding technique significantly impacts model performance
- Linear Regression provides a strong baseline model

---

💡 Conclusion

This notebook successfully demonstrates the end-to-end Machine Learning workflow for car price prediction.
The model achieved a strong R² score of 0.84, showing good predictive capability.

---

🙌 Author

Shweta Rajput
