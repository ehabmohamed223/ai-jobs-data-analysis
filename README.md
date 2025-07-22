<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python Badge"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas Badge"/>
  <img src="https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" alt="Excel Badge"/>
</p>


# AI Jobs Dataset Analysis Project

**Analyzing AI Job Market Trends with Python & Excel**

<img src="https://github.com/user-attachments/assets/625c9170-f626-4542-a850-d63e15bbb512" alt="Model Evaluation Summary" width="100%" />

---

## **Project Overview**

This project focuses on analyzing the **AI job market** by exploring a dataset of over **15,000 AI-related job listings** collected between **2024 and 2025**. The dataset includes detailed information about job titles, salaries, experience levels, required skills, and more.

**Python** used for **data preprocessing and exploding**, and **Microsoft Excel** for **data analysis, visualization, and dashboard creation**.

---

## **Project Goals**

- Understanding the **distribution of AI job roles** across different industries and regions.
- Analyzing **salary trends** and identify top-paying job titles.
- Exploring **required skills** and technologies in the AI job market.
- Investigating the relationship between **experience level** and **job availability/salary**.
- Building a **comprehensive dashboard** for visual insights using Excel.

---


## Data Preprocessing with Python

**Python**  used to clean and transform the dataset for further analysis:

### Tasks Performed:

- **Loading and inspecting** the dataset.
- **Handling missing values** and duplicates.
- **Parsing and exploding** the `required_skills` field to create separate rows for each skill.
- **Extracting date parts** (year, month, day) from `posting_date` and `application_deadline`.
- **Calculating new features** like `days_to_deadline`.
- `required_skills` column were **exploded** to create one skill per row for better filtering options.

### **Data Processing Steps**

To explore the full **data cleaning, preprocessing steps**, view the complete Jupyter Notebook here:  
[Click here to view the AI Jobs Dataset Processing Notebook](https://github.com/ehabmohamed223/ai-jobs-data-analysis/blob/main/Ai_Jobs_Dataset_Processing.ipynb)
