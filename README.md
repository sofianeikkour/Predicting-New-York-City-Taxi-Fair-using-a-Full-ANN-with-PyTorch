# Predicting-New-York-City-Taxi-Fair-using-a-Full-ANN-with-PyTorch

**Context and objective:**  
In this use case, we are tasked with predicting the fare amount for a taxi ride in New York City given the pickup and dropoff locations. This is originally a Kaggle competition we can find on this [link](https://www.kaggle.com/competitions/new-york-city-taxi-fare-prediction/overview). In the description, it is mentionned that we can get a basic estimate based on just the distance between the two points that will result in an RMSE of $5-$8 depending on the model used. The challenge is to do better than this using Machine Learning techniques. In this work, I used a full artificial neural network with the PyTorch framework that I tested on subset of the original dataset, this resulted in an RSME of 3.73.

**Dataset:**  

The dataset contains 6 features and 1 target.
- pickup_datetime: time when the taxi ride started.
- pickup_longitude: longitude coordinate of the pickup ride.
- pickup_latitude: latitude coordinate of the pickup ride.
- dropoff_longitude: longitude coordinate of the dropoff ride.
- dropoff_latitude: latitude coordinate of the dropoff ride.
- passenget_count: the number of passengers.
- fare_amount: this is the target variable indicating the dollar amount of the taxi ride.

Because of computational limitations I have on my computer, I used a subset of 120000 observations from the original dataset that contains 55 million observations.

**Note:** this code was written on Google Colab.  
**Programming language:** Python.  
**Packages:** numpy, pandas, time, pytorch, matplotlib.  
