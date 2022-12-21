# Earthquake_prediction

Earthquake dataset consists of Geographic coordinates and earthquake intensity information.

In this problem, **earthquake intensity > 4.5** should be predicted.

- earthquake intensity > 4.5 to *1*
- other values *0*

**Planets coordinates extracted by solarsystem:**

![alt text](https://github.com/smohammadi96/Earthquake_prediction/blob/main/images/solar.PNG)

**Example**

![alt text](https://github.com/smohammadi96/Earthquake_prediction/blob/main/images/planets.PNG)


Compute **declination** and **Right Ascension** by **solarsystem.Geocentric**

![alt text](https://github.com/smohammadi96/Earthquake_prediction/blob/main/images/ground.PNG)

Convert **declination** and **Right Ascension** to distances and compute theta.

![alt text](https://github.com/smohammadi96/Earthquake_prediction/blob/main/images/1.PNG) 

![alt text](https://github.com/smohammadi96/Earthquake_prediction/blob/main/images/2.PNG)

**Best parameters (XGboost):**

![alt text](https://github.com/smohammadi96/Earthquake_prediction/blob/main/images/3.PNG)

| Model  | Percision | Recall | F1-score | Accuracy | 
| ------------- | ------------- | ------------- | ------------- | ------------- |
| RandomForest  | 0:0.96 - 1:0.45  | 0:0.94 - 1:0.52  | 0:0.95 - 1:0.48 | 0.91 |
| Xgboost 1  | 0:0.95 - 1:0.67  | 0:0.98 - 1:0.43 | 0:0.97 - 1:0.53 | 0.94 |
| Xgboost 2  | 0:0.92 - 1:0.64  | 0:1.0 - 1:0.23 | 0:0.96 - 1:0.15 | 0.92 |
