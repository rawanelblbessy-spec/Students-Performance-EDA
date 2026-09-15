Students Performance in Exams - Exploratory Data Analysis (EDA)

An in-depth Exploratory Data Analysis (EDA) investigating the factors affecting students' performance in exams, using Python, Pandas, and Seaborn.

Project Overview
This project analyzes a dataset containing students' scores in math, reading, and writing, along with various demographic, socioeconomic, and educational background factors. The goal is to uncover hidden patterns, correlations, and actionable insights to improve educational outcomes.

Tech Stack and Libraries

* Language: Python
* Data Manipulation and Analysis: Pandas, NumPy
* Data Visualization: Seaborn, Matplotlib

Key Insights Summary

1. Data Quality: The dataset was exceptionally clean with no missing values and no duplicates.
2. Outliers: Minor low-end outliers were handled primarily in math scores using IQR capping rather than removal to preserve sample size.
3. Score Distributions: All three subject scores (math, reading, writing) are roughly normal, with reading and writing scores slightly left-skewed and more tightly clustered than math.
4. Gender Trends: Females lead in reading and writing; males lead slightly in math.
5. Test Preparation: Completing the test preparation course is strongly associated with a consistent score boost across all subjects.
6. Socioeconomic Factors: Lunch type (acting as a proxy for economic status) and parental education level show a clear positive relationship with average student scores.
7. Correlation: Reading and writing scores move almost together (r = 0.95); math is a comparatively more independent skill.
8. At-risk Group: Students combining low scores, lack of test preparation, and free/reduced lunch form a clearly identifiable high-risk segment.

Recommendations

* Mandatory Test Prep: Encourage or require structured test preparation courses before major exams to elevate overall performance.
* Targeted Nutritional and Support Programs: Support school nutrition programs and targeted assistance for students with free/reduced lunch types to bridge socioeconomic achievement gaps.
* Parental and Academic Support: Provide additional academic support for students with less-educated parents to help balance performance.
* Intervention for At-Risk Segments: Prioritize early-intervention programs combining academic and nutritional support for the identified at-risk student group.

How to Run

1. Clone the repository:
git clone [https://github.com/rawanelblbessy-spec/Students-Performance-EDA.git](https://www.google.com/search?q=https://github.com/rawanelblbessy-spec/Students-Performance-EDA.git)
2. Open the Jupyter Notebook:
jupyter notebook students-performance-in-exams-eda.ipynb
