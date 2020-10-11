# Car-Price-Prediction:
Descriptions:
•	This dataset, scraped from the on-line car trading company in 2019, contains many features of 9 different car models.
•	The features (variables) of this dataset are too messy and distored.

The project aims to conduct a robust predictive model so as to predict the right prices of the cars. The project has 2 phases to reach its goal. First phase focuses on just certain types of cars. Second phase deals with any kind of cars in the sector. On the other hand, However, the features (variables) of this dataset were too messy and distored. Therefore, first phase of the project had to spend more time time than expected as it deals with EDA processes!

My Strategy for EDA Processes:
•	Read the .json file and assign the dataset into a DataFrame using pandas.
•	Implement all aspects of the EDA process to the dataset. 
o	Fix corrupted data formats,
o	Handle with outliers and missing values, 
  	Focus on Domain (automobiles) knowledge.
  	Always use the internet to do the research that you need.
  	Think carefully to decide whether a data is outliers or not. Examples : 
    	There is no conventional car model with an average fuel consumption of 1 - 1.5 liters per 100 km.
    	Or you need to know that it cannot be a 300 euro car.
    	Or if there is only one car with 3 doors out of the 15919 cars, this is what you should pay attention to and examine.
o	Drop the columns / rows you determined unnecessary as a result of your analysis,
o	Use visualization tools while doing all these processes.
•	As a result, get the dataset ready to provide an appropriate input to the ML models.
•	Save cleaned dataset into a .csv file.
