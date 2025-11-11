# Feature Importance
This repository focuses on the topics of Feature Importance and explainable artificial intelligence (XAI).
I first came into contact with this topic during my master's thesis, where I examined the behavior of Permutation Feature Importance in connection to correlated predictor variables. I recently extended this work to include a new model, and summarized my main findings in this [notebook](https://github.com/sevabl/Feature-Importance/blob/main/Permutation%20Feature%20Importance%20-%20Bias%20in%20Correlated%20Predictors.ipynb)
My interest for XAI is fueled by my background in psychology, and the connected research work. For research, it is not as important to improve model accuracy and predictive power as to understand the behavior of the model, and which variables are important for making predictions, and therefore should have some real life relevancy for the outcome of interest.
In many applications this is not of importance, and Data Scientists often only try to improve their predictive accuracy. However, for a significant amount of applications, it is absolutely necessary to not only have an accurate model, but also to understand which variables are relevant, and even better, in which way. 
As a simple example, suppose we try to predict whether a person is likely to develop cancer based on their medical records and certain lifestyle factors. While having an accurate model is crucial for this application, it is also highly relevant to identify relevant predictive variables, especially when these can be actively influenced, in order to minimize risk for the broader population as well as the individuel.

In this repository I will upload notebooks exploring such XAI and feature importance measures.
For anyone wanting a concise and informative introduction to exploring the workings of machine learning models, I can highly recommend the book [Interpretable Machine Learning](https://christophm.github.io/interpretable-ml-book) by Christoph Molnar.

