# AI_PROJECT_TEAM_35


# Introduction to our project

Our project is aimed at addressing the stock prediction problem for predicting the stock price using various AI/ML tools. We used Python, Keras and TensorFlow to predict the price of Goldman Sachs stock.


# Steps

1.	First of all run the STEP_1.ipynb file. It contains importing the Time Series data through API calls from AlphaVantage website and filtering it with proper timestamps and making a ‘initial_data3.csv’ file.

2.	Then run the STEP_2.ipynb file. It contains importing the Technical Indicators to analyze which indicators are affecting the price most. After adding all the top indicators we have made a ‘Final_Data.csv’ file.

3.	After step 2, run DATA_PREP_STEP.ipynb file. It contains train(70%) test(30%) splitting of data to train our LSTM model.

4.	After step 3, run BAYESIAN_NEW_MODEL.ipynb file. It contains loading and inputting the data into our LSTM model using the Bayesian to tune our hyperparameters for better results.

5.	After getting the results from the above step, run FINAL_AI_MODEL_150.ipynb file . Now execute the final Bidirectional LSTM model and plot the result i.e. the predicted vs the real price of stock.
