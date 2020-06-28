# ExploratoryProject
Data analysis of energy consumption in a community and to use predicted statistics to convert a simple Microgrid to a Smart Microgrid, to reduce energy losses.
Due to the challenges faced in operating microgrids, due to variable daily usage of electricity, we have developed a Machine learning model that trains on past data of Electricity consumption and aims to predict a future trend. This can help in improving a microgrid and convert it into a Smart Microgrid.
Data collected is available open source from UK Power Networks.
Out of several features available, we used a few relevant ones. This is decided by observing the correlation between features and target values.
Data link:-https://www.kaggle.com/jeanmidev/smart-meters-in-london
Next, we train the model using the ARIMA model and fit it into an LSTM model.
The model can then be used to make future Electricity consumption, with very little degree of error.
we analysed various model like solar cell,fuel cell ,wind generation and lead battery which is used in microgrid to convert it into smartmicrogrid.
various grafh  analysation has been done on the basis of the data and future prediction model has been made
result
The plot of predicted values of Electricity consumption shows that the Machine Learning model might be doing fairly well. This is confirmed by the plot for the % error which can be clearly seen to be going down. The model fares on a good enough accuracy score of ~93.5%-93%.
This model can now be used for a smart microgrid and reduce large amounts of electrical energy wastage.

