# student_performance
Predicting student final grades using early performance, behavioral, and demographic data; includes regression models, model evaluation, and visualization of influential factors.

Purpose:
Early identification of students at risk of lower performance allows schools 
to intervene proactively. By predicting final grades before midterm evaluations, 
educators can allocate support resources effectively.

Overview: 
This project analyzes student performance data to predict final grades. 
It explores how early academic performance (G1 and G2) and other factors 
such as alcohol consumption, study time, and family support influence outcomes.

Data:
The dataset includes:
- G1, G2: Early term grades
- G3: Final grade (target)
- Dalc: Workday alcohol consumption
- Walc: Weekend alcohol consumption
- Study time, family support, and other behavioral/demographic features

Models:
- Linear Regression
- Lasso Regression
- Support Vector Regression (tuned)

How to Run This Project
1. Clone the repository
git clone https://github.com/helyada/student_performance.git
cd student_performance
2. Install dependencies
pip install -r requirements.txt
3. Run the notebook Open: student_performance.ipynb
Run all cells to reproduce the analysis.

Takeaways:
- Including early grades (G1, G2) significantly improves prediction accuracy.
- RMSE with grades: 2.12, R²: 0.78
- RMSE without grades: 4.19, R²: 0.14
- Alcohol consumption negatively correlates with final grades.
- Early interventions can focus on non-grade factors when grades are not yet available.

Student Academic Performance Dataset:
This dataset is available from the UCI Machine Learning Repository. It contains 30 attributes describing students in mathematics and Portuguese courses. The main objective is to predict each student’s final grade, which ranges from 0 to 20. In this project, the data file used is called student-data.csv (Math).


Data: Student Performance Data Set, Paulo Cortez, UCI Machine Learning Repository, CC BY 4.0
