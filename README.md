# Vehicle
What Drives the Price of a Car

We have acquired a report consisting of used car details over a period of 20+ years. The data included region, price, year, manufacturer, model, condition, cylinders, fuel, odometer, title_status, transmission, VIN, drive, size, type, paint_colr and state. Upon inspection of the data, we removed unnecessary colums (i.e. VIN) and cleansed data of missing values. We explored multiple ways to decide the driving factors behind vehicle prices such as correlations, plots, linear and polynomial regression models. During the process, we split data 70% training and 30% test. Furthermore, we categorized and encoded the string features. The model improved as we utilized additional features. We regularly tested the model with  the test data to ensure the features we included were improving the model. We also learned that the newer the model (year), the more likely the vehicle is purchased. More recent data in 2009 and 2019 were an exception due to the Great Recession and Covid outbreak. Overall we learned the features most valuable in vehicle purchase were the odometer reading, title status, fuel type, and condition. The following was the set of features which resulted in the best results: odometer, transmission, title_status, fuel, cylinders, condition, manufacturer, size, drive, type.

The following can be concluded based on the count plots:
* The more modern the vehicle, the more likely it will be purchased. The small dip in 2009 is due to the "Great Recession" and the more recent count decline since 2019 is due to covid epidemic. The conclusion is, the counts are proportional to the year.
* The manufacturers Chevy, Ford, Toyota, and Honda have the lion-share of the market.
* Buyers only prefer good or excellent condition.
* Purchasers favor only cylinders 4, 6 and 8.
* Purchasers favor gas vehicles.
* Purchasers only favor clean titles.
* Purchasers only favor automatic transmission.
* While purchasers prefer 4wd, 1wd and rwd are also a good percentage of the market.
* When it comes to size, the bigger the more likely it will be purchased.
* For vehicle types, SUV, sedan, pickup and truck are the most purchased.
* Most people prefer white, then black, then silver, then blue, red, and gray.
* Several states like CA, FL, Mi, NY, and TX seem to purchase most vehicles, however other states have sizeable markets.
* The odometer is a top reason for vehicle purchases.


Please note: The vehicle data was too large (> 25 MB) and was refused by Github. The data can be found here: https://mo-pcco.s3.us-east-1.amazonaws.com/BH-PCMLAI-R2/module11/practical_application_II_starter.zip
