# 📊 Insurance Dataset Analysis & Visualization

This project analyzes an **insurance dataset** to explore patterns in medical costs based on factors like age, BMI, smoker status, and region. The analysis includes **visualizations** to highlight key insights. The goal with this project will be to analyze various attributes within insurance.csv to learn more about the patient information in the file and gain insight into potential use cases for the dataset.

---

## 📂 Dataset Overview
The dataset contains **1338 entries** with the following columns:

| Column    | Type   | Description |
|-----------|--------|-------------|
| `age`     | int    | Age of the insured person |
| `sex`     | object | Gender (`male` / `female`) |
| `bmi`     | float  | Body Mass Index |
| `children` | int   | Number of children covered by insurance |
| `smoker`  | object | Whether the person is a smoker (`yes` / `no`) |
| `region`  | object | Residential region (northwest, southeast, etc.) |
| `charges` | float  | Insurance charges in USD |

---

## 📊 Visualizations & Insights

### **1️⃣ Distribution of Insurance Charges**
Shows how **insurance costs are distributed** in the dataset. Most charges are **skewed towards lower values**, but some extreme costs exist.

![Distribution of Insurance Charges](https://user-images.githubusercontent.com/example/distribution.png)

---

### **2️⃣ BMI vs. Insurance Charges**
- **Smokers (colored differently)** tend to have higher medical costs.
- A higher **BMI** often correlates with higher charges.

![BMI vs. Insurance Charges](https://user-images.githubusercontent.com/example/bmi_vs_charges.png)

---

### **3️⃣ Insurance Charges by Smoker Status**
- **Smokers** pay **significantly higher** insurance costs compared to non-smokers.
- Non-smokers have **lower and more consistent** insurance charges.

![Charges by Smoker](https://user-images.githubusercontent.com/example/smoker_charges.png)

---

### **4️⃣ Average Insurance Charges by Region**
- Different **regions** have slightly varying average charges.
- The **s

