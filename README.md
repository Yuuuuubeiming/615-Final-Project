
Breif introduction of the project and use of each file.
      The file is mainly focus on the economics condition in Haiti, including the GDP, national income, unemployment rate, and so on.
There are two datasets used in this project, both of them are downloaded from World Bank website. The first dataset is the Rawdata.xlsx, and after cleaning,
it is called data_clean.csv. It contains the data of these factors from 5 different island countries from 2000 to 2023 and the frequency is 2 years. This datasetvis made for comparing between the countries. In order to make a better prediction, I made another pacakge called Prediction.xlsx which contains the annual GDP and inflation index in Haiti. After cleaning the data, the file names predict_data.csv. All the steps of data cleaning is included in the data_cleaning.rmd.
      In the website, it includes four categories -- overview, map, comparison and prediction. I changed the data into time series and used ARIMA model to do 
the forecasting. The I also draw a residual plot and summary of this prediction, but I did not include them in the website.
