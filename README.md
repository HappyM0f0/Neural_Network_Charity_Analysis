# Neural_Network_Charity_Analysis
 
## Analysis Overview
The purpose of this project is to use deep-learning neural networks with the TensorFlow platform in Python, to analyze and classify the success of charitable donations.

The following methods for the analysis:
- preprocessing the data for the neural network model,
- compile, train and evaluate the model,
- optimize the model.

## Results
### Data Processing
- To clean the data the EIN and NAME columns were removed since they have no value to the model.
- The varibales being considered for the model are as follows: 'STATUS', 'ASK_AMT', 'IS_SUCCESSFUL', 'APPLICATION_TYPE', 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', - 'INCOME_AMT'. I dropped "USE_CASE_Other","AFFILIATION_Other" columns.
- Dependent varible is "IS_SUCCESFUL" since we want to try to predict this with high accuracy.

### Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?
    - 
- Were you able to achieve the target model performance?
    - 
- What steps did you take to try and increase model performance?
    - 


## Summary

The deep learning neural network model did not reach the target of 75% accuracy. Considering that this target level is pretty average we could say that the model is not outperforming.

Since we are in a binary classification situation, we could use a supervised machine learning model such as the Random Forest Classifier to combine a multitude of decision trees to generate a classified output and evaluate its performance against our deep learning model.