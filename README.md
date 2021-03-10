# Delivery-Truck-Ontime-Delay-Prediction

Source data was taken from 
<a href = 'https://www.kaggle.com/ramakrishnanthiyagu/delivery-truck-trips-data'>Kaggle</a>
<br>
<img src='Delivery Truck/truck.gif'>

### Background
Delivering goods from one state to another has been very popular of using trucks. However, more than 35% cases are considered as late/delay shipment.
Even in some case, the delivery supplier managed to got the goods delivered delayed more than 1 month. This is causing anxiousity from the customer that going to use that delivery supplier.

### Goals
- Create a model that able to predict whether the delivery will be delayed or on time
- Decide top 10 features that has the highest ratio to determine the delivery status

### Step
- Eliminate uncorrelated features
- Make some new features that has stronger correlation to the target variable
- Input some missing data with mode and correlated other features
- Try fit model using :
    - Decision Tree Classifier
    - Logistic Regression
    - Gaussian Naive Bayes
    - Random Forest Classifier
    - Gradient Boosting
    - K Nearest Neighbors

Here is the results of the fitted model:
<br>
<img src='Delivery Truck/Result.PNG'>

### Search the Most Important Feature regarding to the prediction
Using best fitted model (Gradient Boosting with accuracy of 89.7%), try to find the feature importance.
Here is the result :
<br>
<img src='Delivery Truck/FI.PNG'>
<br>
10 most important features are :
- GpsProvider
- vehicleType
- vehicle_no
- Distance(Km)
- org_state
- supplierID
- org_city
- des_city
- customerID
- des_state

Hope this repo is helpfull and got you some new insights

Cheers !
Thankyou :)
