# 📊 Customer Churn Analysis (Python Project)

### Predicting and Understanding Why Customers Leave — A Data-Driven Telecom Case Study

A complete **Customer Churn Analysis** project using **Python and Jupyter Notebook** that explores why customers are leaving a telecom company.  
This project showcases **data cleaning, exploratory data analysis (EDA), and business insights** — helping companies improve **customer retention** and **reduce churn rates** through data-driven decisions.


![Python](https://img.shields.io/badge/Language-Python-blue) ![Jupyter Notebook](https://img.shields.io/badge/Tool-Jupyter_Notebook-orange) ![Pandas](https://img.shields.io/badge/Library-Pandas-yellow) ![Matplotlib](https://img.shields.io/badge/Library-Matplotlib-red) ![Seaborn](https://img.shields.io/badge/Library-Seaborn-lightblue) ![NumPy](https://img.shields.io/badge/Library-NumPy-green) ![Data Analysis](https://img.shields.io/badge/Focus-Data_Analysis-blue)

---

## 📊 Project Overview

The objective of this project is to analyze customer data to uncover **key patterns and reasons behind customer churn**.  
By understanding which customers are more likely to leave and why, telecom companies can take proactive steps to **improve loyalty programs**, **optimize services**, and **increase customer lifetime value**.

**Key Goals:**
- Identify major factors influencing customer churn.
- Analyze relationships between contract type, payment method, and churn.
- Visualize churn trends using data visualization libraries.
- Provide actionable insights to reduce customer attrition.

---

## 🛠️ Tools & Technologies Used

| Tool | Purpose |
|------|----------|
| **Python** | Core programming language used for analysis |
| **Jupyter Notebook** | Interactive environment for writing and visualizing code |
| **Pandas** | Data manipulation and cleaning |
| **NumPy** | Numerical operations and data transformation |
| **Matplotlib** | Data visualization and plotting |
| **Seaborn** | Advanced visualization and correlation analysis |

---

## 📁 File Structure

```
│
├── Customer Churn Analysis.ipynb     # Main analysis notebook
├── Customer_churn_data.csv           # Dataset file
├── README.md                         # Project documentation
└── images/                           # Folder containing chart images
    ├── Churn_by_Contract.png
    ├── Churned_by_Payment_Method.png
    ├── Churn_by_SeniorCitizen.png
    ├── Churn_by_Tenure.png
    └── 9_Churned_charts.png
```

---

## 📈 Major Insights by Analysis  

### 🔹 Overall Churn Rate  
- **Loyal Customers (No Churn):** ~73.5%  
- **Lost Customers (Churn):** ~26.5%  

💡 **Insight:**  
Almost **1 in 4 customers** leave the company, indicating a serious retention issue.  
Reducing churn should be a **top business priority** to maintain long-term profitability.

---

### 👩‍💼 Churn by Gender  
- Both **Male** and **Female** customers churn at almost **equal rates**.  

💡 **Insight:**  
Gender does **not significantly influence** churn.  
Retention strategies should instead focus on **contract type, tenure, and service usage**.

---

### 👴 Churn by Senior Citizen Status  
- **Senior Citizens (16%)** show a **much higher churn rate** than younger customers.  
- Nearly **half of senior customers** leave the company.  

💡 **Insight:**  
Senior Citizens are a **high-risk segment**.  
Targeted plans, simplified services, and personalized support could improve their retention.

---

### ⏳ Churn by Tenure (Customer Loyalty)  
- **New Customers (1–12 months)** are the most likely to churn.  
- **Long-term Customers (60+ months)** are much more loyal.  

💡 **Insight:**  
The **first year** of service is crucial for building loyalty.  
Focus on **onboarding, proactive support, and welcome offers** to retain new customers.

---

### 📜 Churn by Contract Type  
- **Month-to-Month contracts** have the **highest churn rate**.  
- **One-Year and Two-Year contracts** show **strong loyalty**.  

💡 **Insight:**  
Encouraging customers to **move from short-term to long-term contracts** through **discounts or bundled benefits** can drastically lower churn.

---

### ⚙️ Churn by Services  

| Service | Churn Risk | Observation |
|----------|-------------|-------------|
| **Phone Service** | 🔸 Low | Minimal effect on churn. |
| **Multiple Lines** | 🔸 Low | Neutral impact. |
| **Internet Service (Fiber Optic)** | 🔴 High | High dissatisfaction and churn among Fiber Optic users. |
| **Online Security** | 🟢 Low | Strong retention driver — customers with it rarely churn. |
| **Online Backup** | 🟡 Medium | Slightly improves retention. |
| **Device Protection** | 🟡 Medium | Minor effect on reducing churn. |
| **Tech Support** | 🔴 Very High | Lack of support leads to major churn. |
| **Streaming TV / Movies** | 🟢 Low | Slight improvement in retention. |

💡 **Insight:**  
**Online Security** and **Tech Support** are the **most powerful loyalty boosters**.  
Bundling these with premium or long-term plans can significantly improve retention.

---

### 💳 Churn by Payment Method  
- **Electronic Check** users churn **most frequently**.  
- **Automatic payments (Credit Card / Bank Transfer)** customers show **higher loyalty**.  

💡 **Insight:**  
Encourage customers to **switch to automatic payment methods** to improve satisfaction and retention.

---

## 📸 Project Preview

### 1️⃣ Churn by Contract
![Churn By Contract](images/Churn_by_Contract.png)

### 2️⃣ Churn by Payment Method
![Churn by Payment Method](images/Churned_by_Payment_Method.png)

### 3️⃣ Churn by Senior Citizen
![Churn by SeniorCitizen](images/Churn_by_SeniorCitizen.png)

### 4️⃣ Monthly Charges vs Churn
![Churn by Tenure](images/Churn_by_Tenure.png)

### 5️⃣ Churn by 9 Charts
![Tenure Impact](images/9_Churned_charts.png)

---

## 🧠 Skills Demonstrated

- ✅ Data Cleaning & Preprocessing  
- ✅ Exploratory Data Analysis (EDA)  
- ✅ Data Visualization & Interpretation  
- ✅ Business Insight Extraction  
- ✅ Python Programming (Pandas, Seaborn, Matplotlib)  
- ✅ Storytelling with Data  
- ✅ Analytical Thinking & Problem Solving  

---

## 🏁 Final Conclusion  

The analysis identifies a clear **pattern of predictable churn**, driven by key factors:

#### 1️⃣ The Loyalty Gap — *Contract & Tenure*  
- **Month-to-month** and **new customers** are at the highest risk.  
- Focus on **annual contracts** and **early engagement programs**.

#### 2️⃣ Value Deficiency — *Support & Security*  
- Customers without **Tech Support** or **Online Security** churn the most.  
- These should be **core service features or recommended add-ons**.

#### 3️⃣ Service Mismatch — *Fiber Optic Dissatisfaction*  
- **Fiber Optic** users churn despite being premium customers, indicating **service quality issues** or **poor value perception**.

#### 🎯 Strategic Recommendations:
✅ Promote **longer-term contracts** to build loyalty.  
✅ Bundle **Tech Support** & **Online Security** with high-value plans.  
✅ Improve **Fiber Optic reliability and customer experience**.  
✅ Implement **onboarding and early retention campaigns** for new users.  
✅ Incentivize **automatic payment methods** to reduce churn risk.

---

## 🧑‍💻 Author

**👤 Harsh Belekar**  
📍 Data Analyst | Python | SQL | Power BI | Excel | Data Visualization  
📬 [LinkedIn](https://www.linkedin.com/in/harshbelekar) | 🔗[GitHub](https://github.com/Harsh-Belekar)

📧 [harshbelekar74@gmail.com](mailto:harshbelekar74@gmail.com)

---

⭐ *If you found this project helpful, feel free to star the repo and connect with me for collaboration!*
