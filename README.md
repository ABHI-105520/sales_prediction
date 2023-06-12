# sales_prediction
This project is about predicting sales using historical data.
The code has 4 parts...

1_SP_data_preprocessing.ipynb, this is the data preprocessing part where data is cleared and useful information is extracted and generate useful data.
2_SP_model.ipynb, this is the machine learning model part, where 4 algorithms(Linear,RandomForest,XGboost,LSTM Regression) are used to predict and generate graphs for data visualization.
3_SP_results.ipynb, this is the model's comparison part to check which model predicted better.
4_SP_newdataupdate.ipynb, this code is for uploading new data to our model.

sales.csv is the file of historical sales data from the year 2013 to 2017
data_2018.csv & data_2019.csv are the two data to be uploaded as new data to predict and evaluating sales of the particular year. This files are to be uploaded in the 4_SP_newdataupdate.ipynb code

NOTE: once the new data is uploaded, the historical data will be altered and updated with the new data and cannot be undone. Upload carefully.
