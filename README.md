#  Bangalore Tech Salary Analysis & Insights

## 📌 Overview

This project analyzes a comprehensive dataset of **tech professionals' salaries in Bangalore** to uncover trends in compensation, experience, roles, and company types. It focuses on transforming messy, real-world salary data into structured insights that reflect hiring patterns and pay distributions in the tech industry.

The project simulates a real-world **HR analytics / compensation benchmarking system** using Python and Pandas.

---

## 📂 Dataset Description

The dataset contains **1000+ employee records** with the following fields:

* **Employee_ID** – Unique identifier
* **Role** – Job role (DS, SDE, PM, DevOps, etc.)
* **years_exp** – Years of experience
* **Current_CTC** – Current salary (mixed formats: LPA, ₹, commas)
* **Previous_CTC** – Previous salary
* **Company** – Employer name
* **company_TYPE** – MNC, Unicorn, Startup, etc.
* **Skills** – Technical skillset
* **Location** – Area within Bangalore
* **Education_Tier** – Tier-1, Tier-2, Tier-3
* **Joining_Year** – Year of joining
* **Work_Mode** – Remote, Hybrid, Onsite

---

## ⚙️ Key Features

### 🔹 1. Data Cleaning & Preprocessing

* Handles inconsistent salary formats (₹, LPA, commas)
* Converts compensation into numeric format
* Cleans missing and duplicate values
* Standardizes categorical columns (education tier, work mode)

---

### 🔹 2. Salary Normalization Engine

* Converts all salary values into a unified metric (LPA)
* Enables accurate comparison across records
* Handles edge cases like string-based salary inputs

---

### 🔹 3. Role-Based Salary Analysis

* Average salary by role (SDE, Data Scientist, PM, etc.)
* Identifies:

  * Highest paying roles
  * Entry-level vs experienced salary gaps

---

### 🔹 4. Experience vs Salary Trends

* Analyzes salary growth with years of experience
* Detects:

  * Salary plateaus
  * High-growth experience ranges

---

### 🔹 5. Company Type Insights

* Compares salaries across:

  * MNCs
  * Unicorns
  * Startups / Early-stage
* Identifies which company type pays the most

---

### 🔹 6. Skills Impact Analysis

* Evaluates how skills influence compensation
* Highlights:

  * High-paying tech stacks (ML, Cloud, Backend, etc.)
  * Skill combinations driving higher CTC

---

### 🔹 7. Work Mode & Location Trends

* Salary comparison across:

  * Remote vs Hybrid vs Onsite
* Location-based insights within Bangalore

---

### 🔹 8. Education Tier Analysis

* Compares salary distribution across Tier-1, Tier-2, Tier-3
* Measures impact of educational background on compensation

---

##  Use Cases

* Salary benchmarking for job seekers
* HR analytics & compensation planning
* Career path decision-making
* Data cleaning & EDA practice
* Portfolio project for data analysts

---

##  Tech Stack

* Python
* Pandas
* NumPy

---

## Outcome

This project demonstrates how raw salary data can be transformed into actionable insights for **career growth, hiring strategies, and market benchmarking**, similar to real-world platforms like compensation intelligence tools and job analytics systems.
