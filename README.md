<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python Badge"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas Badge"/>
  <img src="https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" alt="Excel Badge"/>
</p>


# AI Jobs Dataset Analysis Project

**Analyzing AI Job Market Trends with Python & Excel**

<img src="https://github.com/user-attachments/assets/625c9170-f626-4542-a850-d63e15bbb512" alt="Model Evaluation Summary" width="100%" />


---

## Project Summary

This project focuses on analyzing the **AI job market** by exploring a dataset of over **15,000 AI-related job listings** collected between **2024 and 2025**. The dataset includes detailed information about job titles, salaries, experience levels, required skills, and more.

We used **Python** for **data preprocessing and exploding**, and **Microsoft Excel** for **data analysis, visualization, and dashboard creation**.

---

## 🎯 Project Goals

- Understand the **distribution of AI job roles** across different industries and regions.
- Analyze **salary trends** and identify top-paying job titles.
- Explore **required skills** and technologies in the AI job market.
- Investigate the relationship between **experience level** and **job availability/salary**.
- Build a **comprehensive dashboard** for visual insights using Excel.

---

## 🛠️ Tools & Technologies

- **Python** – For data preprocessing, cleaning, and exploding nested fields.
- **Pandas** – For data manipulation and transformation.
- **Excel** – For exploratory data analysis, visualization, and dashboard creation.









---

## 📁 Dataset Overview

The dataset contains the following key fields:

| Column Name | Description |
|-------------|-------------|
| `job_id` | Unique identifier for each job listing |
| `job_title` | Title of the job (e.g., ML Ops Engineer, NLP Engineer) |
| `salary` | Annual salary offered |
| `currency` | Currency used (e.g., USD, EUR, GBP) |
| `experience_level` | Experience required (Associate, Master, PhD, etc.) |
| `required_skills` | Skills required for the job |
| `industry` | Industry the job belongs to (e.g., Gaming, Healthcare, Energy) |
| `location` | Country and city where the job is based |
| `employment_type` | Full-time, Part-time, Contract, etc. |
| `posting_date` | Date when the job was posted |
| `application_deadline` | Deadline for applying |
| `company_name` | Name of the hiring company |
| `days_to_deadline` | Days between posting and deadline |
| `benefits_score` | Score representing job benefits |

> 📌 *Note:* Some fields like `required_skills` were **exploded** to create one skill per row for better analysis.

---

## 🧹 Data Preprocessing with Python

We used **Python** to clean and transform the dataset for further analysis:

### ✅ Tasks Performed:

- **Loading and inspecting** the dataset.
- **Handling missing values** and duplicates.
- **Parsing and exploding** the `required_skills` field to create separate rows for each skill.
- **Extracting date parts** (year, month, day) from `posting_date` and `application_deadline`.
- **Calculating new features** like `days_to_deadline`.
