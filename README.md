# pandas-challenge
Pandas

# Overview of the analysis:
The purpose of this analysis is to create a machine learning model to help determine and predict which applicants will have success in their projects and should receive funding. The goal is to use TensorFlow to create a model then optimize it to increase the accuracy. 

# Results:
1. Original model received accuracy of 72.5%
2. Optimized model received accuracy level of 79%

# Data Preprocessing:

1. What variable(s) are the target(s) for your model?
  **Answer** The target is the Is_Successful column

2. What variable(s) are the features for your model?
  **Answer** Feature list of this model are: name, application type, afiliation, classification, use_case, organization, income, special consideration, status, and ask amount

3. What variable(s) should be removed from the input data because they are neither targets nor features?
  **Answer** EIN (Employee identification number)

# Compiling, Training, and Evaluating the Model:

1. How many neurons, layers, and activation functions did you select for your neural network model, and why?
  **Answer** For this model 3 hidden layers each with many neurons because the compute seems to increase the accuracy above 75%. This is expensive and costly. The first activations is relu and the other layers are sigmoid it might boost accuracy using the functions. Readjusting my data that names as a get dummies can factor in with better scores.

2. Were you able to achieve the target model performance?
  **Answer** Yes

3. What steps did you take in your attempts to increase model performance?
  **Answer** I was required to convert the NAME into data points which has the biggest impact on improving the efficiency but costly as it requires adding a third layer using sigmoid activation function. 

# Summary: 
Overall the accuracy is above 75% and we are able to correctly classify each in the test data 75% of the time. An applicant has an 80% chance of being success if they follow -
  Name of applicants appears more than 5 times
  Type of applications following T3, T4, T5, T6, T7, T8, T10, T19
  Application of following classification ...

# Recommendation:
We can try using a RandomForest ML algorithm because it is known for high accuracy and help predict good applicants to fund that will yield a successful outcome. 
