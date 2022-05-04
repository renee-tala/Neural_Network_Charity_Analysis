# Neural Network Charity Analysis

## Overview of the analysis

This analysis uses machine learning and neural networks with Tensorflow to predict whether applicants will be successful if funded by Alphabet Soup. The data provided from Alphabet Soup contains 34,000 plus organizations that have received funding. 

- With this data, we will:
  - preprocess the data for the neural network
  - complie, train, and evaluate the neural network model
  - conduct additional trainings to optimize the model

- Resources:
  - charity_data.csv
  - Pandas, Python, Jupyter Notebook

## Results: Using bulleted lists and images to support your answers, address the following questions.

### Data Preprocessing
What variable(s) are considered the target(s) for your model?
What variable(s) are considered to be the features for your model?
What variable(s) are neither targets nor features, and should be removed from the input data?

### Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
Were you able to achieve the target model performance?
No. 

Three attempts were made to increase model performance. 
  1. The second hidden layer was increased from 30 units to 40 units. The output activation was changed to 'RELU'.
  2. A third hidden layer was added with 20 units
  3. The activation was changed to 'TANH'. 

## Summary: 
Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
The model could not meet the target performance, even with three more attempts. 
