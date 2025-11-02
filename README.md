#🎓College Course Feedback Analysis: Task 3
  

## Objective  

This project analyzes student feedback data collected after college courses.  
The goal is to understand which factors influence student's satisfaction and course recommendations.

## Dataset Overview  
Each row represents feedback from one student, including ratings (1–10) for:  
- Subject Knowledge  
- Concept Clarity  
- Use of Presentations  
- Assignment Difficulty  
- Doubt Solving  
- Course Structure  
- Extra Support  
- Course Recommendation  

**Rows:** 1000+  
**Columns:** 8 numeric features  

## Analysis Performed  
- Cleaned and simplified dataset columns  
- Checked overall statistics and missing values  
- Calculated correlations between feedback parameters  
- Identified key drivers for course recommendation  
- Visualized relationships between parameters  

## Key Insights  
- *Subject Knowledge* and *Concept Clarity* show a **slight positive relation** with Course Recommendation.  
- *Assignment Difficulty* has a **negative correlation**, meaning easier assignments tend to improve satisfaction.  
- Most students gave **moderate ratings (5–7)** for most parameters.  
- *Extra Support* had minimal impact on recommendation scores.

## Tools & Libraries  
- Python   
- Pandas  
- Matplotlib  
- Seaborn  
- NumPy  

## Visualizations  
- Correlation Heatmap  
- Average Ratings Bar Chart  
- Distribution Plot of Course Recommendations  

## File Details  
- `College_Event_Feedback_Analysis.ipynb` – Jupyter Notebook  
- `student_feedback.csv` – Dataset file  

## Learnings  
This project helped me strengthen my understanding of data analysis workflow —  
from cleaning and exploring data to visualizing correlations and drawing actionable insights.
