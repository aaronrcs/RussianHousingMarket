# RussianHousingMarket


__Team Members:__
 
Cedric Tong,            	
Wilbert Veit,            	
Gonzalo Serrano,     	
Aaron Romero,        	
Avik Gharzarian     	
 
__Project Title:__
 
Sberbank Russian Housing Market(Gathered from Kaggle.com)
 
__Project Description:__
 
Sberbank is Russia’s oldest and largest bank that helps their customers by making predictions about realty prices so renters, developers, and lenders are more confident when they sign a lease or purchase a building. Due to the country’s volatile economy, forecasting prices imposes a unique challenge. Complex interactions between housing features, locations, and pricing makes the predictions more complicated. In addition, an unstable economy means Sberbank and their customers need more than simple regression models to predict prices. The aim of this project is to predict the sale price of each property. 

__Data:__

The target variable is called __price_doc__ in the train.csv file.

- __train.csv and test.csv:__ they hold information regarding transactions. Each Row in these files are indexed by an “id”, which refers to -individual transactions. These files also include supplementary details about local area of each person.

- __macro.csv:__ This file contains details about Russia’s macroeconomy and financial sector; this file can be joined to the test and train csv files on the “timestamp” column.

- __BAD_ADDRESS_FIX.xlsx:__ There was a problem with coordinates for some properties which lead to errors in distance parameters, because they were calculated from the heart of Moscow for such cases, which is wrong. This file fixes the parameters.

__Goals:__

-	After looking at our data, one of our goals in this project was to find out a way to shrink the amount of features (our data consisted of 200+ features)
-	Also find out a way to exclude the rows and columns that contained NaN values without shrinking our data too much. And trying to get the best accuracies predicting on our target variable. 

-	Although our data is based around regression models, we wanted to experiment with classifiers as well, and compare accuracies.

