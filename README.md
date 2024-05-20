# classification-challenge

I will have developed two classification models to fit the provided data and evaluate which one is more accurate at detecting spam. The models I created are a logistic regression model and a random forest model.

### This challenge consists of the following subsections:

  1. Split the data into training and testing sets.
  2. Scale the features.
  3. Create a logistic regression model.
  4. Create a random forest model.
  5. Evaluate the models.
--- 
--- 

1. Split the Data into Training and Testing Sets
Open the starter code notebook and complete the following steps
   * Read the data from this link into a Pandas DataFrame.
   * In the appropriate markdown cell, make a prediction as to which model you expect to perform better.
   * Create the labels set (y) from the “spam” column, and create the features (X) DataFrame from the remaining columns.
   * Check the balance of the labels variable (y) using the value_counts function.
   * Split the data into training and testing datasets using train_test_split.

2. Scale the Features
   * Create an instance of StandardScaler.
   * Fit the StandardScaler with the training data.
   * Scale the training and testing features DataFrames using the transform function.

3. Create a Logistic Regression Model
   * Fit a logistic regression model using the scaled training data.
   * Save the predictions on the testing data labels using the testing feature data and the fitted model.
   * Evaluate the model’s performance by calculating the accuracy score.

4. Create a Random Forest Model
   * Fit a random forest classifier model using the scaled training data.
   * Save the predictions on the testing data labels using the testing feature data and the fitted model.
   * Evaluate the model’s performance by calculating the accuracy score.

5. Evaluate the Models
   * Which model performed better?
   * Compare the accuracy scores of both models and determine which one has a higher score.
   * How does that compare to your prediction?
   * Reflect on your initial prediction and discuss whether the results aligned with your expectations.

### My Final Steps
I ensure you that all my code and markdown cells are properly documented and organized.
I pushed the final version of my notebook to my GitHub repository.
