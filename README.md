# Health Costs Calculator

Using a large data frame contained in the [Free Code Camp Machine Learning course](https://www.freecodecamp.org/learn/machine-learning-with-python/#how-neural-networks-work) the goal was to use Multiple Linear Regression to know the health expenses of a patient knowing the following information:

- Age
- Sex
- BMI
- Number of children the patient has
- If the patient is a smoker or not
- The region

The dataset used in this study initially included expense information for all patients. However, to build and evaluate the Multiple Linear Regression model using Keras, the dataset was split into training and testing datasets.

After being trained and evaluated, the final model was able to predict the health costs for a particular patient with a Mean Absolute Error of $3100.
