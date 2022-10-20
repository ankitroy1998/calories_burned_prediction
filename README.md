# calories_burned_prediction
Machine Learning (Random Forest Regressor) + Streamlit

Calories Burned Prediction

Objective:
Machine Learning is a category of algorithms that allows software applications to become more accurate in predicting outcomes without being explicitly programmed. The basic premise of machine learning is to build models and employ algorithms that can receive input data and use statistical analysis to predict an output while updating outputs as new data becomes available. These models can be applied in different areas and trained to match the expectations, so that accurate steps can be taken to achieve the output. The object of this research paper is to create a project that can be used predict calories need to burn using Machine Learning with Python.

Description:
Initially we have collected two datasets for calories and exercise, prepared the data (Data Visualization) for model training. After preparation we divided the datasets in Test (20%) and Train (80%) dataset. 
We trained the models using Test dataset, models used: Linear Regression, Decision Tree, Random Forest, with an accuracy of 96.68%, 99.37%, 99.81% respectively.
So, we generated our final model using the Random Forest Regressor.
We used Streamlit to create a web-based application in order to interact directly with the final model.

Requirements:
Front End: Streamlit (Python)	
Backend: Machine Learning Model (Python)
Software: Jupyter Notebook, Visual Studio Code

Conclusion:
The mean absolute error value that is getting in Random Forest Regressor is around 0.180 which is a good value. The error values are very less. Therefore, we can conclude that the best model for the calorie burn prediction is Random Forest Regressor.

References: https://scikit-learn.org/stable/ , https://seaborn.pydata.org/
