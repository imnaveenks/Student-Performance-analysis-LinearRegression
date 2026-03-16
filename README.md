# Student Performance Analysis

## Overview

This project looks at what actually predicts how a student performs at the end of the year. I used a dataset of 395 Portuguese high school students and built a linear regression model to predict their final grade.

## Key Finding

A student's grades from the first two terms are by far the strongest signal. Once you include those, the model predicts final grades with 87% accuracy. Study time, absences, and parental education add some value but nowhere near as much as prior performance. The practical takeaway is that schools do not need to wait until the end of the year to know who is struggling. The pattern is visible as early as term one.

## Results

| Model | R2 | RMSE |
|---|---|---|
| Study time only | 0.007 | 4.07 |
| 5 variables | 0.053 | 4.35 |
| Full model (inc. G1, G2) | 0.870 | 1.48 |

## Variables Used

Study time, past failures, absences, mother's education, father's education, first term grade, second term grade

## Tools

Python, Pandas, Scikit-learn, Matplotlib, Google Colab

## Dataset

UCI Student Performance Dataset
