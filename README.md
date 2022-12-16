# Estimation-of-Tropospheric-Ozone

Ozone has been one of the crucial gases in the atmosphere but while stratospheric ozone is essential for protecting us from the UV rays on the other hand the tropospheric ozone is the major pollutant and a cause for lung disease. 

Estimate of Tropospheric Ozone is done by using the AQ-bench dataset which is a cleaned dataset. It has data 5577 records from different parts of the world from 2010 to 2014. This has been the benchmark model which we build up. 

We used the modes of feature engineering and made the features more related to things which could have mattered for the reaction to take place and dug into the details of release of the reactants and their sources (VOCs and NOx), the amount of O2 and the water present which are all integral parts of the reaction to form ozone in the troposphere. 

On the machine learning front we used to ensemble methods to fit the model better. We used the voting regressor with the SVR and the gradient boosting regressor as the voters. 

The below figures show the performance of the models with and without feature engineering

<img width="221" alt="image" src="https://user-images.githubusercontent.com/73403218/208025348-49253788-4586-43d9-9e47-bd4bf696d8fa.png">

The below figure shows how models perform on the data after feature engineering is done.

<img width="239" alt="image" src="https://user-images.githubusercontent.com/73403218/208024914-8c8ef85d-0c30-4ae8-9f5a-4fa8dbb0ca6f.png">
