# Student Academic Performance Analysis

## Table of Contents

- [Introduction](#introduction)
- [Problem Statement](#problem-statement)
- [Data Collection](#data-collection)
- [Data Checks](#data-checks)
- [Feature Wise Visualization](#feature-wise-visualization)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Deployment](#deployment)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Introduction

This project aims to understand the influence of various factors such as parents' background, test preparation, etc., on students' academic performance. Analyzing student performance is crucial as it allows educators to assess and improve teaching methods. Many factors can influence a student's performance, including the parents' educational background, test preparation, student health, and more.

---

## Problem Statement

Analyzing student work is an essential part of teaching. Teachers assign, collect, and examine student work regularly to assess student learning and to revise and improve teaching. Ongoing assessment of student learning allows teachers to engage in continuous quality improvement of their courses. This project seeks to understand how various factors, including parental background and test preparation, impact student performance.

---

## Data Collection

- **Dataset Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams?datasetId=74977)
- **Dataset Information**: The dataset comprises 8 columns and 1000 rows detailing the marks secured by students in various subjects. The columns are:
  - gender
  - race/ethnicity
  - parental level of education
  - lunch
  - test preparation course
  - math score
  - reading score
  - writing score

---

## Data Checks

Before diving into the analysis, it's essential to ensure the data's integrity:
- Check for missing values.
- Verify there are no duplicates.
- Confirm the data types of each column.
- Examine the number of unique values in each column.
- Review the dataset's statistics.
- Investigate the categories present in the categorical columns.

---

## Feature Wise Visualization

This section delves into the insights derived from the data:
- Distribution of gender and its impact on performance.
- Influence of lunch type on exam scores.
- The effect of parental education on student performance.
- Score distributions for different subjects.
- Demographic insights based on ethnicity, lunch type, test preparation, and parental education.

---

## Model Training and Evaluation

For this project, two models were trained to predict student performance: Xgboost and Catboost. After rigorous training and evaluation, the models achieved an accuracy of 88%.

---

## Deployment

The trained model has been deployed using Flask, making it accessible for real-time predictions. To run the application, use the `app.py` script.

---

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/nani2357/ML_project_Students-Performance-in-Exams_with-Deployment.git

