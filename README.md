# Data Science Projects

## 1. Analaysis of Rossmann Drugstore Sales

- There was the initial data cleaning stage where the number of missing values in the dataset were either imputed or dropped.
- Exploratory Data Analaysis (EDA) was carried out to analyse trends in the dataset so that patterns or changes in the sales during different periods of time could be analysed. 
- Bar charts, line graphs, time series plots and a correlation matrix were some of the data visualisation techniques used to gain valuable insights to our data, which gave an insight on how to proceed to the next step.
- Machine Learing (ML) models such as Lasso and Ridge regressions were used for forecasting future stock prices.
- The regression models did give us a good R^2 value, but we managed to improve it further by implementing Decision trees and Random Forest models as well.
- At the end of the project, we essentially came up with a time series prediction model that forecasted the next 4 weeks of sales from its current date.
- We finally ended the project while a model outputting an R^2 value of 0.997.

## 2. Stock Portfolio Optimisation

- The dataset given consisted of different data types such as strings, floats and time series data.
- There was many missing NaN values that were identified, so forward and backward filling methods were used to fill in these missing values.
- EDA was performed on the top 10 US stocks, and the stock performance was analysed for the entire 26 years.
- Time series plots were done to analyse the trends of how the stock prices for the 10 companies changed over time, since the data was originally a time series data.
- Modelling techniques such as regressions like Lasso, Ridge and Linear were analysed to forecast the stock prices from 2020-2025.
- Other methods of modelling included Decision trees, Random forest, ARIMA and a DL model like LSTM were also used to further the quality of the forecasting.
- Although newer methods like LSTM were used, the accuracy of the models were not as high. In the end, Ridge regression performed the best on average.
- Finally, a diversified portfolio was created with ratios of the different risk tolerances for each of the top 10 stocks, so that investors could plan ahead on which stocks woule be the best to invest in so as to minimise risk and maximise capital.

## Analaysis of Malaria in Red Blood Cells

- This was the first time I dealt with a dataset that did not contain any numerical data. The zip file contained two files named "Uninfected" and "Parasitized", with each containing more than 13,000 images.
- EDA was carried out to analyse the various different cell shapes and colour filters for each individual image in order to identify any patterns within the dataset.
- It was quicky identified that there were misclassified images, meaning images that contained cells that were malaria-free were classified as "Parasitized", and vice versa.
- Models such as Single-Layer Perceptron, Multi-Layered Perceptrons (MLP), K-Means Clustering and K-Fold Out-of-Fold (OOF) were used to deal with the misclassifications.
- A Convolutional Neural Network (CNN) model was developed to help with the image classification of both sets of data, which gave a high testing accuracy of 91.74%.
- From this model, further improvements to the CNN model were made to increase the testing accuracy and handle image classification better.
- Transformations such as rotation, flips, crops and colour adjustmetns, increasing the number of layers and adding a scheduler increased the testing accuracy to 98.16%.
- Using the scheduler, the number of epochs was 50 and the model prevented overfitting and sved time. 
