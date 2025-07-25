# 🎓 Student Performance Analysis Project

This project explores a real-world **student exam performance dataset** to uncover factors that influence academic achievement.  
It includes full **Exploratory Data Analysis (EDA)** in Python and a **Power BI Dashboard** with interactive insights.

---

## 📌 Objectives
- Perform detailed **EDA** using **Pandas, Matplotlib, Seaborn**.
- Answer 8 key questions about performance differences by gender, lunch, test prep, and parental education.
- Identify top-performing students and analyze their demographic patterns.
- Group students into **performance categories** using clustering.
- Build an interactive **Power BI Dashboard** with clear visuals and slicers.

---

## 📂 Project Files
- **StudentPerformanceAnalysis.ipynb** – Jupyter Notebook with cleaning, EDA, and clustering.
- **StudentsPerformance.csv** – Original dataset (Kaggle: *Students Performance in Exams*).
- **StudentPerformance_Dashboard.pbix** – Interactive Power BI dashboard.

---

## 🧪 Jupyter Notebook – EDA Highlights

**Data Cleaning:**
- Checked for duplicates and missing values – none found.
- Renamed columns for easier access.

**Business Questions Answered:**
1. **Parental education vs. math score** – Higher parental education correlates with higher math performance.
2. **Gender differences** – Females lead in reading and writing; math scores are close.
3. **Test prep effect** – Completing the test prep course significantly improves all scores.
4. **Top 10% combinations** – Students with **female gender + standard lunch + completed test prep** dominate the top scorers.
5. **Lunch type across ethnic groups** – Free/reduced lunch consistently impacts all groups, with variations by race/ethnicity.
6. **Correlations between scores** – Reading and writing scores have the strongest correlation.
7. **Top 5% performers** – Mostly females with completed test prep and higher parental education.
8. **Performance clusters (Low, Medium, High)** – Created using Pandas quantiles and confirmed with K-Means.

**Visuals:**
- Score distributions (histograms)
- Gender/lunch/test prep comparisons (bar charts)
- Correlation heatmap
- Clustering scatter plot (reading vs writing)

---

## 📊 Power BI Dashboard

### **Page 1 – Performance Overview**
- KPI Cards: Average Math, Reading, Writing scores.
- Bar Chart: Average scores by gender.
- Histogram: Distribution of average scores.
- Slicers: Gender, Race/Ethnicity, Test Preparation Course.

### **Page 2 – Factors Affecting Performance**
- Bar Charts: Math scores by parental education; scores by lunch; scores by test prep.
- Table: Top 10% performers by gender, lunch, and test prep.
- Slicers: Gender, Race/Ethnicity, Test Preparation.

### **Page 3 – Correlation & Clusters**
- Matrix heatmap (approximate correlations between scores).
- Scatter Plot: Reading vs. Writing, colored by performance category.
- Bar Chart: Students per performance category.

### **Page 4 – Top Performers & Demographics**
- Table: Top 5% performers with demographics.
- Bar Charts: Top performers by gender; by lunch & test prep.
- Pie Chart: Race/Ethnicity breakdown.
- Slicers: Gender, Lunch, Race/Ethnicity.

---

## 🛠 Tools & Technologies
- **Python 3** (Pandas, Seaborn, Matplotlib)
- **Jupyter Notebook**
- **Power BI Desktop**
- **Kaggle Dataset**

---

## 📌 Dataset Source
Kaggle – [Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)

---

## 📩 Questions?
Feel free to fork, star ⭐, or connect with me on GitHub!

