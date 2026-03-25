📊 Customer Data Analysis – Capstone Project
📌 Project Overview

This project is a Python Fundamentals Capstone Project focused on performing data analysis using Pandas and NumPy.

The objective is to work with multiple datasets, clean missing values, transform data, and generate meaningful insights through structured tasks.

🗂️ Dataset Description

The project uses three datasets:

1. Employee Data
Column	Description
ID	Unique employee ID
Name	Project head name
Gender	Male (M), Female (F)
City	Project location
Age	Project duration (years)
2. Seniority Level Data
Column	Description
ID	Employee ID
Designation Level	Position level (1 = Highest, 4 = Lowest)
3. Project Data
Column	Description
ID	Employee ID
Project	Project name
Cost	Project cost
Status	Finished / Ongoing / Failed
⚙️ Technologies Used
Python 🐍
Pandas 📊
NumPy 🔢
Jupyter Notebook 📓
🚀 Tasks Performed
✅ Task 1

Created three DataFrames and saved them as .csv files.

✅ Task 2

Handled missing values in the Cost column using a running average (for loop).

✅ Task 3

Split the Name column into:

First Name
Last Name
✅ Task 4

Merged all three datasets into a single DataFrame named Final.

✅ Task 5

Added a Bonus column:

5% bonus for employees with Finished projects
✅ Task 6
Reduced designation level by 1 for failed projects
Removed employees with designation level > 4
✅ Task 7
Added Mr./Mrs. prefix to First Name
Dropped Gender column
✅ Task 8

Promoted designation level by 1 for employees with Age > 29

✅ Task 9

Created a new DataFrame TotalProjCost:

ID
First Name
Total Project Cost
✅ Task 10

Filtered employees whose city contains letter 'o'

📈 Key Learnings
Data Cleaning & Preprocessing
Handling Missing Values
Data Transformation
Data Merging (Joins)
Conditional Logic in Pandas
Aggregation & Grouping
