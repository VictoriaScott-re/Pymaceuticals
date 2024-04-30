# Pymaceuticals
Module 5 Assignment


resources:

https://matplotlib.org/stable/gallery/statistics/boxplot.html 
- This helped me to change the outlier color to red in my Quartiles section

https://chat.openai.com/


https://stackoverflow.com/questions/45670487/numpy-cov-exception-float-object-has-no-attribute-shape
- I found this source that really helped me understand the error message I was getting. It explained that the error occurs when you're using NumPy arrays with a dtype of object. This dtype can cause issues with certain NumPy functions, as the note in the source mentions.

- To fix the problem, the source suggests converting the array to a numeric type using .astype(float) before passing it to the NumPy function. This way, the function doesn't encounter any issues with the array's dtype.

- In my code, I encountered a similar problem with my arrays, capomulin_mouse_weight and capomulin_avg_vol. They were likely dtype object instead of a numeric type. By converting them to numeric types, just like the source suggested, I was able to resolve the AttributeError and get my code running smoothly again. 
