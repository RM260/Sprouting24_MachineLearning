# Model Training and Validation with California Census Data

## Lesson Guide

By the end of this lesson, you will understand the importance of splitting data into training and test sets to prevent overfitting and evaluate your model's ability to generalize. You will also learn how different loss functions and regularization techniques can improve model performance by balancing prediction accuracy and complexity.

**`Coding` Explore and Understand the California Housing Dataset**

Our dataset is from `sklearn`. Most datasets obtained from `sklearn` have a `.DESCR` attribute, which provides a description of the dataset.

**`Coding` Instantiate a Linear Regression Class and Fit a Linear Model**

Reference the documentation of the `LinearRegression` class from `sklearn` to figure out how to instantiate a linear regression class and then fit a model. Navigate to the examples portion of the documentation.

* [Linear Regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html)

**Evaluating Model Fit**

Using the following concept, interpret the model score, which outputs the $r^2$ value for your model fit and answer the following question.

* What does the $ r^2 $ value tell us about our model?
* [What is the correlation coefficient, r, for linear least squares regression with a single independent variable?](https://www.notion.so/What-is-the-correlation-coefficient-r-for-linear-least-squares-regression-with-a-single-independen-3cbd32a278504dc9a8725a308a5fdb34?pvs=21)


Also, discuss the following concepts that are pivotal to assessing model fit.

[What is underfitting?](https://www.notion.so/What-is-underfitting-13308e5d878f800180aedfedc638375d?pvs=21)

[What is overfitting?](https://www.notion.so/What-is-overfitting-13308e5d878f805f9e15f6c5d1f5e70c?pvs=21)

[What is a good fit?](https://www.notion.so/What-is-a-good-fit-13308e5d878f808187a4e86d52ad3c8a?pvs=21)

**`Coding` Evaluate the Model**

First, calculate the $r^2$ score and the mean squared error to evaluate the model’s performance using the following function:

- `model.score()`
- `mean_squared_error()`

**`Coding` Visualize the Model**

Create a scatter plot of the true versus predicted values using the following functions:

- `model.predict()` and
- `plt.scatter()`
    
    

**`Coding` Linear Regression with Train and Test Splits**

Fit two models where first you don’t split your data, and second you do split your data. To split your data, use `train_test_split()`  from `sklearn.model_selection` . The documentation for this is here:

* [Train Test Split](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html)
