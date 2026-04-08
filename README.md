# Project5ML-Mental-Health-in-Tech-Survey

# 🧠 Mental Health in Tech Survey - EDA Project

## 📌 Project Overview
This project analyzes mental health trends in the tech industry using survey data.

Completed as part of the **Innovexis Internship Program**.

---

## 📂 Dataset Information

### 📄 File: survey.csv

The dataset contains survey responses from employees in the tech industry.

### 🔑 Key Columns:
- Age → Age of respondent  
- Gender → Gender identity  
- Country → Work location  
- family_history → Mental illness history  
- treatment → Treatment taken or not  
- work_interfere → Impact on work  
- benefits → Mental health benefits  
- remote_work → Work mode  
- mental_health_consequence → Fear of consequences  

---

## ⚙️ How to Perform This Project

### Step 1: Import Libraries
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

### Step 2: Load Dataset
```python
df = pd.read_csv("survey.csv")
```

---

### Step 3: Data Understanding
- `df.head()`  
- `df.info()`  
- `df.describe()`  

---

### Step 4: Data Cleaning
- Remove unnecessary columns  
- Handle missing values  
- Clean gender and age  
- Remove duplicates  

---

### Step 5: Exploratory Data Analysis
Follow UBM Rule:
- Univariate  
- Bivariate  
- Multivariate  

---

### Step 6: Visualization
- Create 20+ charts  
- Use seaborn & matplotlib  
- Add insights for each chart  

---

### Step 7: Key Insights
- Mental health issues are common  
- Family history impacts treatment  
- Benefits improve support  
- Workplace culture matters  

---

### Step 8: Business Recommendations
- Provide mental health benefits  
- Increase awareness  
- Create safe environment  
- Encourage communication  

---

## 📁 Project Structure
```
Mental-Health-EDA/
│
├── Mental_Health_EDA.ipynb
├── survey.csv
└── README.md
```

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## 👩‍💻 Author
- Bhumika Patil
- Innovexis Intern  
