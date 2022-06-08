# Classification-Predictive-Modeling

APPROACH:

Aim is to create a model that has to  predict whether the user will buy the product or not based on previous activity data. So it's a clear Classification problem.

Start with Data Wrangling —->Feature selection—>Base Model —--> Improve the model F1 scorers

In data wrangling performed. 1)Treating missing values
      		2)Data type conversion
		3)Drop the unwanted features
Feature Selection
	
1)Correlection check as two features user_activtiy 6  and 7 look similar.   So I removed one feature.
2)Created_at feature and sign_up feature difference can give the exact number month difference between them. So we find out that and drop former features.

Model Training:
	Tried with various classification algorithms and finally chosen XGBoosting algorithm works better. 
