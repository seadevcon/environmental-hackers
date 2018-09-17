This main part of the Project was created while the Seadevcon Hackathon was taking place (07. - 08.09.18).


The FeatureEngeneering notebook contains the cleaning of the seadevcon table. Afterwards there will be no NaN values left in it. 

In Modelling.ipynb I used Random Forrest algorithm to predict what fuel the ship is using depending on all 81 parameters left. I also used Random Forrest for forecasting and got a high accuracy of predicting on what fuel the ship will be going (up to about) 100 min in the future. But the results should be used with caution! The most relevant features are accRunTime and RunNumber, so the Model is clearly overfitting to the history of this ship and engine. Sadly, while the Hackathon, I did not have the time to correct this and after the Hackathon I had to delete all the data.

The Some_Data_Analysis merges Seadevcon and Runlog to give an overview about the use of gas/gasdiesel/diesel and heavy oil over the years.
