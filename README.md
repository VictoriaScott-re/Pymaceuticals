# Pymaceuticals
Module 5 Assignment

Background
You've just joined Pymaceuticals, Inc., a new pharmaceutical company that specializes in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

The executive team has tasked you with generating all of the tables and figures needed for the technical report of the clinical study. They have also asked you for a top-level summary of the study results.

Instructions
This assignment is broken down into the following tasks:

Prepare the data.

Generate summary statistics.

Create bar charts and pie charts.

Calculate quartiles, find outliers, and create a box plot.

Create a line plot and a scatter plot.

Calculate correlation and regression.

Submit your final analysis.

resources:

https://matplotlib.org/stable/gallery/statistics/boxplot.html 
- This helped me to change the outlier color to red in my Quartiles section

https://chat.openai.com/


https://stackoverflow.com/questions/45670487/numpy-cov-exception-float-object-has-no-attribute-shape
- I found this source that really helped me understand the error message I was getting. It explained that the error occurs when you're using NumPy arrays with a dtype of object. This dtype can cause issues with certain NumPy functions, as the note in the source mentions.

- To fix the problem, the source suggests converting the array to a numeric type using .astype(float) before passing it to the NumPy function. This way, the function doesn't encounter any issues with the array's dtype.

- In my code, I encountered a similar problem with my arrays, capomulin_mouse_weight and capomulin_avg_vol. They were likely dtype object instead of a numeric type. By converting them to numeric types, just like the source suggested, I was able to resolve the AttributeError and get my code running smoothly again. 
