# Capstone Project: Bike Sharing Demand Prediction
In today’s time, many of the urban cities around the world harbor considerably large population. Owing to the large population, daily commuters need mobility options which are available close at hand, and that is why many urban cities around the world have introduced rental bikes system. Providing the commuters with stable supply of rental bikes at each hour the day becomes a challenge. So, the objective of the project is to build a regression model that predicts the count of rental bikes required at each hour every day.

### Following were the approaches taken:
•	Null values and outliers in the dataset were inspected and handled. 

•	Exploratory Data Analysis: Bike demand across months and hours of the day, relation between numerical features and bike demand.

•	<ins>Building LINEAR MODELS</ins>: 

a)	Data preprocessing and feature engineering.

b)	Feature selection using: correlation matrix, VIF analysis and feature statistical significance.

c)	Training LINEAR, RIDGE & LASSO regression models along with hyper parameter tuning.

d)	Model evaluation.

•	<ins>Building TREE BASED MODELS</ins>: 

a)	Training DECISION TREE, RANDOM FOREST, GRADIENT BOOSTING and EXTREME GRADIENT BOOSTING regression models.

b)	Hyper parameter tuning.

c)	Model evaluation. 

### **CONCLUSIONS**:

•	The bike demand across months is non-monotonic, with lowest demand in winters, increasing till June in summers and then increases and decreases till November in autumn season.

•	The pattern of bike demand is different for weekdays and weekends.

•	On weekdays, there is a huge surge/ spike during morning 8 am and evening 6 pm indicating those being office going and returning hours, respectively.

•	On weekends, there is no peak in the morning as weekdays, indication that people have their weekends off at work and the maximum demand is in the evening, but lesser than normal weekdays.

•	The relation of hour of the day and rented bike count is non-monotonic.

•	The demand of bikes on non-weekend holidays follow similar pattern to that on weekends.

•	Temperature has the highest positive correlation of 0.54 with bike demand. Wind speed and solar radiation are also positively correlated. 

•	Humidity, Rainfall and Snowfall are negatively correlated with bike demand.

•	All linear models performed almost similar, with R2 score of around 0.7 for both test and train test.

•	All tree based models perform better than linear models, with Extreme Gradient Boosting regression giving the best results: R2 train- 0.967, R2 test- 0.913.

