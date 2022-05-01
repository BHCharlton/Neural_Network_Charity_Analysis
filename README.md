# Neural_Network_Charity_Analysis

## Overview of the Analysis

Using my knowledge of machine learning and neural networks, I'll be analyzing the features in the provided dataset to develop a binary classifier that is capable of predicting whether applicants will be successful if funded by the charity group Alphabet Soup.  The dataset provided by Alphabet Soup's business team contains information about more than 34,000 organizations that have received funding from Alphabet Soup over the years.  The dataset is made up of several different columns of metadata about each organization, of which I will preprocess to compile a neural network model capable of predicting whether applicants seeking funding by Alphabet Soup will be successful.  The model will need to be trained and evaluated for it's efficacy, then optimized multiple times to ensure reliable results.

## Results
### Data preprocessing:
  * The target variable for the model will be "IS_SUCCESSFULL," which is the ultimate question to be assessed by the model
  * The variables "EIN" and "NAME" will be dropped because the data contained does not provide information that would have any significant effects on the outcome
  * All other variables in the dataset provide useful information that can improve model accuracy and will be considered useful features for the model

### Compiling, Training, and Evaluating the Model:
For the initial model evaluation, two hidden layers were used.  The first hidden layer contained 8 neurons, while the second hidden layer contained 5.  Both hidden layers had the "relu" activation function applied, while the output layer used the "sigmoid" activation function instead.  The figures for the initial evaluation were selected simply to create a generalized framework for optimization comparison. 

![NNCA1](https://user-images.githubusercontent.com/93561592/166168312-f5ccdfa9-7536-43fb-9205-aaf5fe673052.PNG)

At only 52.41%, the initial evaluation did not produce very good results in accuracy.  So for model optimization, new figures and functions will be applied to new evaluation to see if accuracy can be improved

There were several adjustments made to each evaluation in an effort to improve the model's accuracy.  Some of the steps used were adding new hidden layers, changing the neuron counts, changing the activation types, and adjusting the number of epochs used when running the model.  While some improvements were made during optimization, they were minimal at best.

![NNCAL](https://user-images.githubusercontent.com/93561592/166169222-e08b3be7-d045-42e8-b0cf-07b24dbf9813.PNG)

Unfortunately, the accuracy target of 75% was not acheived during the optimization phase.

## Summary
