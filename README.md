# RussianHousingMarket

__Team Members:__
 
Cedric Tong,            	
Wilbert Veit,            	
Gonzalo Serrano,     	
Aaron Romero,        	
Avik Gharzarian     	
 
__Project Title:__
 
Sberbank Russian Housing Market
 
Project Description:
 
Sberbank is Russia’s oldest and largest bank that helps their customers by making predictions about realty prices so renters, developers, and lenders are more confident when they sign a lease or purchase a building. Due to the country’s volatile economy, forecasting prices imposes a unique challenge. Complex interactions between housing features, locations, and pricing makes the predictions more complicated. In addition, an unstable economy means Sberbank and their customers need more than simple regression models to predict prices. The aim of this project is to predict the sale price of each property. 

Data:

The target variable is called price_doc in the train.csv file.

train.csv and test.csv: they hold information regarding transactions. Each Row in these files are indexed by an “id”, which refers to individual transactions. These files also include supplementary details about local area of each person.

macro.csv: This file contains details about Russia’s macroeconomy and financial sector; this file can be joined to the test and train csv files on the “timestamp” column.

BAD_ADDRESS_FIX.xlsx: There was a problem with coordinates for some properties which lead to errors in distance parameters, because they were calculated from the heart of Moscow for such cases, which is wrong. This file fixes the parameters.
