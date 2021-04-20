# Bangalore-House-Predcition
 
Predicting house prices in Bengaluru

### Data:
The train and test data will consist of various features that describe that property in Bengaluru.
Each row contains fixed size object of features. There are 9 features and each feature can be accessed by its name.

### Features:
<ul>
 <li>Area_type – describes the area</li>
 <li>Availability – when it can be possessed or when it is ready(categorical and time-series)</li>
 <li>Location – where it is located in Bengaluru (Area name)</li>
 <li>Size – in BHK or Bedroom (1-10 or more)</li>
 <li>Society – to which society it belongs</li>
 <li>Total_sqft – size of the property in sq.ft</li>
 <li>Bath – No. of bathrooms</li>
 <li>Balcony – No. of the balcony</li>
 <li>Target variable:</li>
 <li>Price – Value of the property in lakhs(INR)</li>
</ul> 

### Train dataset:<br>
Contains all the features and target variable.<br>
Contains 13,321 records.<br>

### Test dataset:<br>
Contains all the features.<br>
Contains 1,481 records.<br>
 
 
### Problem statement:
With the given 9 features(categorical and continuous) build a model to predict the price of houses in Bengaluru.


### Evaluation Metric:<br>
Root-Mean-Squared-Error (RMSE) between the logarithm of the predicted price value and the logarithm of the observed sales price.<br>
Taking logs means that errors in predicting expensive houses and cheap houses will affect the result equally.<br>
