## 🎓 Student Performance & Academic Success Factors
## 📌 Project Overview
This project explores the relationship between a student's socio-economic background and their academic performance. By analyzing a dataset of 1,000 students, we investigate how factors such as parental education, lunch programs, and test preparation impact standardized scores in Math, Reading, and Writing.

## 📂 Dataset Information
Source File: students1.csv

Size: 1,000 unique student records.

Feature Set:

Categorical: Gender, Race/Ethnicity, Parental Education, Lunch Type, Test Prep Course.

Numerical: Math Score, Reading Score, Writing Score.

Engineered Features: Total Score, Average Score, Pass/Fail Status (Threshold: 60%).

## 🛠️ Technical Stack
Data Engineering: Python (Pandas) for data cleaning and metric calculation.

Exploratory Analysis: Jupyter Notebook (Seaborn/Matplotlib) for correlation and distribution studies.

Business Intelligence: Microsoft Power BI for interactive dashboarding and DAX modeling.

##🚀 Key Implementation Steps
1. Data Transformation (Python)
Developed a Pass/Fail logic based on the mean of three subjects.

Aggregated scores to create a unified Overall Average metric.

Verified data integrity by ensuring no null values or score outliers (0-100 range).

2. Statistical Findings
The Prep Factor: Students who completed the preparation course scored an average of 10 points higher than those who did not.

Parental Education: A direct linear correlation was observed between higher parental degrees (Master's/Bachelor's) and higher student median scores.

The Literacy Link: Discovered a 0.95 correlation between Reading and Writing scores, suggesting these skills are developed interdependently.

3. Power BI Dashboard Features
KPI Cards: Instant visibility into Total Students, Overall Average, and the class Pass Rate.

Impact Visuals: Clustered bar charts showing the "Prep Course" lift per subject.

Demographic Drill-down: Slicers for Lunch and Gender to analyze equity in performance.

Scatter Plot: Visualizing the literacy correlation and identifying "Math Specialists."

##💡 Strategic Insights
Targeted Support: Students from "Some High School" parental backgrounds or "Free/Reduced" lunch status show the highest need for supplemental academic resources.

Focus Areas: While Reading and Writing are linked, Math scores are more independent, requiring a separate, specialized tutoring approach.

Preparation Value: Data proves that mandated test preparation could significantly narrow the performance gap across all demographics.
