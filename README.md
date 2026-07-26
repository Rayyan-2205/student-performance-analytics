# 📊 Student Performance Analytics System

## Overview

This project analyzes student performance using Python and Pandas. The goal is to understand how different factors such as self-study hours, attendance, and class participation affect students' overall academic performance.

This is my first end-to-end data analysis project. I built it to practice working with real datasets and to improve my data analysis skills using Pandas.

---

## Dataset

The dataset contains information for **1,000,000 students** with the following columns:

* Student ID
* Weekly Self Study Hours
* Attendance Percentage
* Class Participation
* Total Score
* Grade

---

## Project Workflow

### 1. Data Exploration

* Loaded the dataset
* Checked the shape and data types
* Examined summary statistics
* Verified the dataset structure

### 2. Data Cleaning

* Checked for duplicate records
* Checked for missing values
* Verified attendance, study hours, and score ranges
* Generated a data cleaning report

### 3. Feature Engineering

Created new columns to make analysis easier:

* Attendance Category
* Study Hour Category
* Performance Category

---

## Data Analysis

The project answers questions such as:

* What is the average student score?
* Which performance category has the highest attendance?
* Which study category performs the best?
* Which participation level has the highest average score?
* How do grades compare in terms of score, attendance, and study hours?
* Who are the top and bottom performing students?

---

## Visualizations

The project includes the following charts:

* Performance Category Distribution
* Attendance Category Distribution
* Study Hour Category Distribution
* Average Score by Participation Level
* Average Score by Study Category

All charts are saved in the **images/** folder.

---

## Project Structure

```
Student-Performance-Analytics/
│
├── data/
├── images/
├── output/
├── main.py
├── requirements.txt
├── README.md
└── .gitignore
```

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib

---

## Key Insights

Some of the findings from this analysis include:

* Students who study more hours generally achieve higher scores.
* Better attendance is associated with better academic performance.
* Higher class participation is linked to improved average scores.
* Most students fall into the higher performance categories.
* Creating meaningful categories makes large datasets easier to analyze.

---

## What I Learned

This project helped me understand how a complete data analysis workflow is performed. I practiced:

* Data exploration
* Data cleaning
* Feature engineering
* GroupBy operations
* Aggregation
* Data visualization
* Exporting analysis results
* Organizing a project for GitHub

Although this is my first analytics project, it gave me practical experience with working on a large dataset and building an end-to-end data analysis project.
