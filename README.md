
# Week1: 📘 Student Performance – EDA

## 🔹 Project Overview

This project is part of my Data Science internship (Week 1).
The main goal is to analyze student exam scores and discover patterns based on factors such as **gender, lunch type, parental education, and test preparation course**.

The project focuses on:

* Exploring the dataset
* Visualizing trends
* Understanding how different factors influence performance
* Summarizing insights in a clear and meaningful way

## 📂 Dataset

The dataset used is from Kaggle:
👉 [Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)

It contains the following key features:

* **Gender**
* **Parental level of education**
* **Lunch type** (standard or free/reduced)
* **Test preparation course** (completed or not)
* **Scores** in Math, Reading, and Writing


## ⚙️ Tools & Libraries

* **Python** (Pandas, Matplotlib, Seaborn)
* **Google Colab / Jupyter Notebook**
* **GitHub** for version control and sharing

## 📝 Methods & Workflow

1. **Data Loading & Exploration** – Load CSV, check structure, and basic stats.
2. **Data Cleaning** – Verify missing values and handle if required.
3. **Feature Engineering** – Added an `average_score` column for overall performance.
4. **Score Analysis** – Used `groupby()` to compare scores across gender, parental education, lunch type, and test preparation.
5. **Visualization** – Created bar plots, box plots, violin plots, and a correlation heatmap.
6. **Insights & Conclusion** – Summarized the key findings in simple terms.


## 📊 Key Insights

1. Students who completed the **test preparation course** scored **10–15 points higher** on average.
2. **Standard lunch students** performed better across all subjects compared to free/reduced lunch.
3. **Female students** outperformed in **reading & writing**, while **male students** had a slight edge in **math**.
4. **Parental education level** showed a positive influence on performance, especially in reading.
5. There is a **strong correlation between reading and writing scores (r > 0.9)**.


## ✅ Conclusion

This analysis highlights how **test preparation, lunch quality, gender, and parental education** significantly influence student performance.
The findings suggest that academic success is not just about natural ability but also depends on **environmental and social factors**.

Such insights can help educators and policymakers design better **student support systems** to improve learning outcomes.

## 🚀 How to Run This Project

1. Clone this repository
   ```bash
   git clone https://github.com/<your-username>/Week1-StudentPerformance-EDA.git
   ```
2. Open the notebook in Google Colab or Jupyter.
3. Run all cells to reproduce the analysis and visualizations.


✨ **End Note:**
This was my first week’s project in Data Science — a beginner-friendly yet insightful dive into analyzing real-world data.

---
