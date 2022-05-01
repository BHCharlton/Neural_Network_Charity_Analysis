# Neural_Network_Charity_Analysis

## Overview of the Analysis

Using my knowledge of machine learning and neural networks, I'll be analyzing the features in the provided dataset to develop a binary classifier that is capable of predicting whether applicants will be successful if funded by the charity group Alphabet Soup.  The dataset provided by Alphabet Soup's business team contains information about more than 34,000 organizations that have received funding from Alphabet Soup over the years.  The dataset is made up of several different columns of metadata about each organization, of which I will preprocess to compile a neural network model capable of predicting whether applicants seeking funding by Alphabet Soup will be successful.  The model will need to be trained and evaluated for it's efficacy, then optimized multiple times to ensure reliable results.

## Results
### Data preprocessing:
  * The target variable for the model will be "IS_SUCCESSFULL," which is the ultimate question to be assessed by the model
  * The variables "EIN" and "NAME" will be dropped because the data contained does not provide information that would have any significant effects on the outcome
  * All other variables in the dataset provide useful information that can improve model accuracy and will be considered useful features for the model

### Copiling, Training, and Evaluating the Model:
  * For the ini
