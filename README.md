# Project: Linear Regression Algorithm README

## Introduction
Reggie, a mad scientist working on the newest ball pit for a local fast food joint, has embarked on a mission to optimise the bounciness of different balls based on their sizes. This project aims to assist Reggie in implementing a linear regression algorithm in Python to find the best fit line that minimizes the error between the observed bounces and the predicted bounces of various ball sizes.

## Objective
The main goal is to develop a linear regression function that predicts the bounciness of balls in the ball pit, ensuring an optimal play experience. By experimenting with different sizes of bouncy balls and recording their bounce heights, we aim to fit a line to these data points that best represents their relationship.

## Methodology
### Part 1: Calculating Error
- Implement a `get_y()` function to calculate the `y` value for a given `x` on a line defined by `y = m*x + b`.
- Develop a `calculate_error()` function to measure the distance between a point and a line, serving as the error for a given set of `m`, `b`, and a point.
- Validate these functions with test cases to ensure accuracy.

### Part 2: Finding the Best Fit
- Explore a range of `m` (slope) and `b` (intercept) values to find the line that minimizes the total error for the dataset.
- Use list comprehensions to generate `possible_ms` and `possible_bs` for trial and error.
- Implement nested loops to calculate the total error for all possible lines, keeping track of the `m` and `b` values that result in the smallest error.

### Part 3: Model Prediction
- With the best fit line determined, use the model to predict the bounce height of a ball with any given width.
- Verify the model's prediction accuracy with a test case.

## Implementation
- Functions such as `get_y(m, b, x)`, `calculate_error(m, b, point)`, and `calculate_all_error(m, b, points)` form the core of the linear regression model.
- Through iterative comparison of total errors for various `m` and `b` combinations, identify the optimal line of best fit.
- Apply the model to predict outcomes for new data points not included in the initial dataset.

## Conclusion
This project demonstrates the fundamental principles of linear regression, showcasing how mathematical concepts can be applied to practical scenarios like optimizing a ball pit's design. By calculating the line of best fit, Reggie can make informed decisions about the selection of ball sizes to ensure the highest quality of play experience in the ball pit.

Reggie's experiment and subsequent linear regression model provide a foundation for further exploration into predictive modelling and data analysis, highlighting the importance of understanding data relationships and error minimization in creating effective solutions.
