# Project: Student Performance Analysis

## Overview
This project analyzes a dataset containing students' exam scores and demographic information to uncover insights about factors influencing student performance. The project involves detailed **Exploratory Data Analysis (EDA)** using Python (Pandas) and a visual representation of the findings through a **Power BI Dashboard**.


## Dataset
- **Source**: [Students Performance in Exams – Kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)
- **Columns**:
  - `gender`
  - `race/ethnicity`
  - `parental level of education`
  - `lunch`
  - `test preparation course`
  - `math score`
  - `reading score`
  - `writing score`

---

## Objectives
- Perform comprehensive EDA to uncover patterns and trends.
- Answer tricky and meaningful business questions, such as:
  1. Which parental education level is linked with the highest average math score?
  2. Is there a significant score difference between males and females across all subjects?
  3. How much does completing the test preparation course improve performance in each subject?
  4. Which combination of gender, lunch type, and test preparation status produces the top 10% of scores?
  5. Does lunch type impact performance uniformly across race/ethnicity groups?
  6. What is the correlation between reading and writing scores compared to math and writing?
  7. Identify the top 5% performing students and analyze their demographic profiles.
  8. Can students be clustered into performance categories using only Pandas?

---

## Tools & Technologies
- **Python**: Pandas, NumPy, Matplotlib, Seaborn
- **Power BI**: For creating the dashboard and visualizing insights

---

## Key Features of the Dashboard
- KPI cards displaying average scores for each subject
- Bar charts and visual comparisons across gender, parental education, and lunch type
- Slicers for:
  - Gender
  - Lunch type
  - Test preparation course
- Performance category distribution visualization
- Pie chart for gender-based average scores

---

## Key Insights
- Students whose parents hold **master's degrees tend to have higher average scores**.
- Completing a **test preparation course positively influences performance across all subjects**.
- A strong **positive correlation exists between reading and writing scores**, stronger than math and writing.
- Gender differences are relatively minor, with **females slightly outperforming in reading and writing**, and **males in math**.

---

## Files Included
- `eda.ipynb`: Python code for data cleaning, EDA, and analysis
- `StudentPerformanceDashboard.pbix`: Power BI dashboard file
- `README.md`: Project overview and documentation

---

## How to Use
1. Clone this repository.
2. Open the Jupyter Notebook/Colab file and run the code cells sequentially.
3. Open the `.pbix` file in Power BI to explore the interactive dashboard.

---

## Learnings & Skills Gained
- Enhanced **EDA techniques** and ability to extract business insights from data.
- Hands-on experience in creating **interactive Power BI dashboards**.
- Improved understanding of **data visualization best practices**.

---

## Future Improvements
- Incorporate machine learning models to predict student performance.
- Add more demographic factors if available for deeper insights.
- Create automated pipelines for continuous data analysis.

---

## Author
**Mariam Khan**  
Bootcamp Project – Student Performance Analysis  
