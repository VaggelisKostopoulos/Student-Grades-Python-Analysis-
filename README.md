Student Grades Analysis

This project explores and analyzes a dataset of 37,000+ students and their academic performance.
The dataset originally contained 15 columns, where I removed 1 column and added 2 new ones during preprocessing.

The main goal of this project was to clean the data, perform exploratory analysis, and create insightful visualizations using Matplotlib and Seaborn.

Dataset Overview

Columns used in the analysis:

Gender

EthnicGroup

ParentEduc (Parent Education)

TestPrep (Test Preparation)

ParentMaritalStatus

PracticeSport

IsFirstChild

NrSiblings

WklyStudyHours (Weekly Study Hours)

Total_Score (Aggregated score)

Grade (Categorical grade: Fail → Excellent)


Data Cleaning & Preparation

Removed irrelevant column(s).

Added 2 engineered features.

Handled missing, duplicates or inconsistent values.

Removed rows with a lot of NaN values.

Transformed categorical variables for better analysis.


Analysis & Visualizations

Using Matplotlib and Seaborn, I generated various plots:

Bar plots for categorical averages. 

Box plots for distributions.

Stacked and grouped bar charts for categorical comparisons 

Pie charts for proportions 

Key Findings

Students who studied 5–10 hours weekly achieved the best grades. Both understudying and overstudying led to worse performance.

Students with higher-educated parents had higher average scores.

Students who practiced sports regularly performed better on average compared to those who rarely or never did.

Female students achieved higher average grades compared to male students.

Tools & Libraries

Python

Pandas – data manipulation

Matplotlib – data visualization

Seaborn – statistical plots

Conclusion

The project highlights how study habits, parental education, sports activity, and gender can influence student performance.
These insights can help educators and policymakers design strategies to improve student outcomes.
