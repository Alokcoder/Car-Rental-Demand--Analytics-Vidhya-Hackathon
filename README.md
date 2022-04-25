# Car-Rental-Demand--Analytics-Vidhya-Hackathon
The main objective of the problem is to develop the machine learning approach to forecast the demand of car rentals on an hourly basis.

Approach:

Feature engineering of the date played a major role in the model preparation .

Step taken to build model:
•	Label encoding of month according to the demand 
•	Label encoding of day according to the demand
•	Column to specify if it’s a weekend or not 
•	Column to specify if it’s a public holiday
•	Column to specify if the demand was during working hours 
•	XGBOOST Regressor for prediction
