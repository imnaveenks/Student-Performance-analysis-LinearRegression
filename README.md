Student Performance Analysis
Overview
This project looks at what actually predicts how a student performs at the end of the year. I used a dataset of 395 Portuguese high school students and built a linear regression model to predict their final grade.
Key Finding
A student's grades from the first two terms are by far the strongest signal. Once you include those, the model predicts final grades with 87% accuracy. Study time, absences, and parental education add some value but nowhere near as much as prior performance. The practical takeaway is that schools don't need to wait until the end of the year to know who is struggling. The pattern is visible as early as term one.
Results
ModelR²RMSEStudy time only0.0074.075 variables0.0534.35Full model (inc. G1, G2)0.8701.48
Variables Used
Study time, past failures, absences, mother's education, father's education, first term grade, second term grade
Tools
Python, Pandas, Scikit-learn, Matplotlib, Google Colab
Dataset
UCI Student Performance Dataset
