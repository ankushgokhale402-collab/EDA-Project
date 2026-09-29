# EDA-Project
# 🧹 Data Cleaning Mini Project with Python

A beginner-friendly **Data Cleaning project using Python and Pandas**.
In this project, a messy student admission dataset is cleaned and transformed into a structured, consistent, and analysis-ready dataset.

The project is designed to demonstrate the basic but important steps involved in real-world data cleaning.

---

## 📌 Project Overview

The dataset represents student admission records from a coaching institute.

The original dataset contains common real-world data quality issues such as:

* Missing values
* Duplicate records
* Extra spaces
* Inconsistent capitalization
* Different spellings for the same course
* Numbers stored as text
* Commas inside numeric values
* Invalid ages
* Marks greater than 100
* Different date formats
* Unknown/missing admission dates

The goal is to clean these issues and create a reliable dataset that can be used for further analysis.

---

## 🎯 Objectives

The main objectives of this project are:

1. Understand the structure of a messy dataset.
2. Identify missing and duplicate records.
3. Standardize column names.
4. Clean text data.
5. Standardize course names.
6. Convert columns to appropriate data types.
7. Detect and handle invalid values.
8. Handle missing values using suitable techniques.
9. Validate the cleaned dataset.
10. Export the cleaned dataset as a CSV file.

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Google Colab**
* **Jupyter Notebook**

## The notebook imports Pandas and NumPy for data manipulation and cleaning. Matplotlib is used later for a simple course-wise visualization.

## 📊 Dataset

The project creates a sample dataset directly inside the notebook, so no external dataset upload is required.

The original dataset contains **12 rows and 7 columns**:

| Column           | Description         |
| ---------------- | ------------------- |
| `student_name`   | Name of the student |
| `age`            | Student age         |
| `city`           | Student's city      |
| `course`         | Enrolled course     |
| `fees`           | Course fees         |
| `marks`          | Student marks       |
| `admission_date` | Date of admission   |

The initial dataset contains 12 rows and 7 columns.

---

## 🔍 Data Quality Problems

The project intentionally includes several types of data-quality problems.

### Examples

| Problem                      | Example                               |
| ---------------------------- | ------------------------------------- |
| Extra spaces in column names | `" Student Name "`                    |
| Duplicate row                | Rahul Sharma appears twice            |
| Mixed capitalization         | `priya verma`, `AMIT PATEL`, `INDORE` |
| Extra spaces                 | `"Sneha Joshi "`                      |
| Text instead of number       | `"twenty"`                            |
| Invalid age                  | `-5`, `150`                           |
| Comma in number              | `"25,000"`                            |
| Invalid marks                | `250`                                 |
| Different date formats       | `2026-01-10`, `15/01/2026`            |
| Different course spellings   | `UI/UX`, `UI UX`, `Full stack`        |
| Missing values               | `None`, `NaN`                         |

These issues are explicitly introduced in the n
