# RetailExercise

In this project I had the opportunity to run some basic Time Series Analysis tests, using the retail data.

The goals for this project were:
Conduct Time Series Analysis on the dataset
Plot the Time Series
Plot the Autocorrelation Function and the Partial Autocorrelation Function

For this exercise I used the libraries:
tidyverse, xts, zoo
I used the Online Retail dataset from the UCI website.

In this Time Series analysis exercise I set out to construct a time series plot to observe trends in the sales period of December 2010 through December 2011. To start, I created time series object with the start date of 2010's December with a quarterly frequency. Then I encoded many date columns to more easily aggregate them. Once aggregated, the time series objects would be analyzed to find periodicity, plots, ACF and PACF.

The time series data was already clean and therefore I did not need to impute or remove missing fields. As the data covers only one year, no meaningful seasonality effects can be discerned. 
