# NYC Public School SAT Performance Analysis

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Analysis-SAT_Performance-blue?style=for-the-badge)

An analytical project focused on evaluating the SAT performance of New York City public schools to assist stakeholders in identifying academic trends and regional disparities.

## 📌 Project Objectives

1.  **Identify Top Performers**: Rank schools based on average math scores and total SAT performance.
2.  **Borough Analysis**: Group data by borough to find average scores and identify which regions have the highest variability (standard deviation) in performance.
3.  **Educational Insights**: Provide a statistical foundation for researchers and parents to evaluate school quality across NYC.

## 📂 Project Structure

* `notebook.ipynb`: The primary analysis notebook containing data cleaning, aggregation, and statistical reporting.
* `schools.csv`: The core dataset containing school names, boroughs, and average scores for Math, Reading, and Writing.

## 🚀 Key Technical Features

* **Advanced Grouping**: Utilized `groupby` and `agg` to perform multi-variable statistical analysis on school boroughs.
* **Score Synthesis**: Created a calculated `total_SAT` field to provide a holistic view of school performance beyond individual subjects.
* **Variance Detection**: Focused on identifying the borough with the largest standard deviation in SAT scores to highlight educational disparity.

## 📊 Summary of Findings

* **Elite Schools**: Identified Stuyvesant High School and Bronx High School of Science as the city's top SAT performers.
* **Regional Disparity**: Manhattan was identified as having the largest standard deviation in scores (std: 230.29), indicating a wide gap between its top-tier and lower-performing schools.

---
**Author:** [Your Name]
