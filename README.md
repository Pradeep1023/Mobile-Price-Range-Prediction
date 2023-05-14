# Mobile-Price-Range-Prediction
![image](https://github.com/Pradeep1023/Mobile-Price-Range-Prediction/assets/112772717/a09b4b36-de86-430d-8114-7c628e1eb79a)

![image](https://github.com/Pradeep1023/Mobile-Price-Range-Prediction/assets/112772717/9de1a2d6-a977-4f8e-8cb3-28780def693f)

**Table of Content**

Introduction

Problem Statement

Data Description

Steps Involved

Algorithms Used

Conclusion

![image](https://github.com/Pradeep1023/Mobile-Price-Range-Prediction/assets/112772717/1d119fef-feb3-443f-b406-3a2b5a0c48ee)

**Introduction**

The price range of mobile devices is a key factor that influences consumer decisions in the ever-evolving smartphone market. As technology continues to advance and new features are introduced, mobile prices can vary significantly across different brands and models. Understanding the mobile price range landscape is essential for consumers who seek to find the right balance between their budget and desired specifications. manufacturers and industry analysts rely on accurate price range information to gauge market competitiveness and develop effective pricing strategies. This introduction delves into the importance of mobile price ranges, exploring how they impact consumer choices and the dynamic nature of the mobile industry.

![image](https://github.com/Pradeep1023/Mobile-Price-Range-Prediction/assets/112772717/b7ccb9df-843f-4cf0-8973-3aa027d60b12)

**Problem Statement**

In the competitive mobile phone market companies want to understand sales data of mobile phones and factors which drive the prices.
The objective is to find out some relation between features of a mobile phone(eg:- RAM, Internal Memory, etc) and its selling price. 
In this problem, we do not have to predict the actual price but a price range indicating how high the price is.

![image](https://github.com/Pradeep1023/Mobile-Price-Range-Prediction/assets/112772717/e3af940f-6377-4550-9fb4-40c7d4a2f840)

**Data Description**

Battery_power - Total energy a battery can store in one time measured in mAh

Blue - Has bluetooth or not

Clock_speed - speed at which microprocessor executes instructions

Dual_sim - Has dual sim support or not

Fc - Front Camera mega pixels

Four_g - Has 4G or not

Int_memory - Internal Memory in Gigabytes

M_dep - Mobile Depth in cm

Mobile_wt - Weight of mobile phone

N_cores - Number of cores of processor

Pc - Primary Camera mega pixels

Px_height - Pixel Resolution Height

Px_width - Pixel Resolution Width

Ram - Random Access Memory in Mega Bytes

Sc_h - Screen Height of mobile in cm

Sc_w - Screen Width of mobile in cm

Talk_time - longest time that a single battery charge will last when you are

Three_g - Has 3G or not

Touch_screen - Has touch screen or not

Wifi - Has wifi or not

Price_range - This is the target variable with value of 0(low cost), 1(medium cost), 2(high cost) and 3(very high cost).

![image](https://github.com/Pradeep1023/Mobile-Price-Range-Prediction/assets/112772717/6060879a-afc9-4470-b276-53dca0b0c8c9)

**Steps Involved**

Data Preprocessing:  Checked for outliers, null values, duplicated values and changed data type. Some features have zero value so replaced it with their mean value. 

Exploratory Data Analysis: Performed EDA on discrete and continuous features with various graphs and plots to better understand the distribution of features and their relationships.

Feature Engineering: Plotted heatmap to check the correlation between features, some features were highly correlated like pixel hight and pixed width,screen height and screen width, so performed feature engineering and taken area of the features.

Implemented different classification algorithms

Hyperparameter tuning

![image](https://github.com/Pradeep1023/Mobile-Price-Range-Prediction/assets/112772717/bc7baec5-89da-46f6-86f1-ec235f104f59)

**Algorithms Used**

Logisitc Regression

Decision Tree Classifier

Decision Tree with Cross-validation

Random Forest Classifier

XG Boost

K-Nearest Neighbors

Support Vector Machine Classifier

![image](https://github.com/Pradeep1023/Mobile-Price-Range-Prediction/assets/112772717/4792705f-a73b-4a99-92f0-513490044140)

**Conclusion**

Most of the mobile phones supports 3G i.e. 76% while only 52% mobile phones support 4G.

Only 50% of mobile phone has bluetooth and 51% of mobile phones has dual sim feature.

The cost of the 4G mobile phones is higher than other phones.

RAM, battery power, and pixels have strong correlation with mobile price range. If any of them increases, price range also increases.

XG Boost and SVM performed best among these algorithms with test accuracy score of 91%.

![image](https://github.com/Pradeep1023/Mobile-Price-Range-Prediction/assets/112772717/80bb39e9-c80f-4bfc-9aa3-309f80323f0c)
