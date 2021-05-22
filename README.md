# Crime Analysis Project 

This is Crime Analysis project written in Python.
Our main goal was to predict various crimes numbers in each city in the US.
At first we had to crawl to the FBI website to pull the crime statistics, after that we downloaded 10 datasets of crime statistics per city of 2010-2019.
In addion, we download another datasets of law enforcement statistics per city.
Prior the EDA part we came to a conclution that although we have lots of crime statistics per city it will be insufficient for the ML part. So, we decided to swich to a State level instead the City level.
After we switched to State level we shrinked our dataset and lost lots of data. 
We found lots of data in a State level (from KFF.org) and we again had to edit, fill , merge all the data into a single dataframe to work with on the EDA and ML parts.

In the ML part we used the Linear Regression and Ridge models.
With both models we wanted to predict the year 2019 and compare with the actual crime numbers which we have already gathered.
Linear Regression: We managed to predict 3 crimes: Property crime, Vehicle theft, Aassault.
Ridge: With this model we predicted all the crimes we had in the Dataframe using all the DataFrame features.
At the end we ploted all the predicted crimes numbers into US map and wanted to see the our prediction for the year 2019.
