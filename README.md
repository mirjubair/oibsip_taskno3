# Car Price Prediction with Machine Learning

**Oasis Infobyte Internship Project** - [**Credentials**](https://drive.google.com/file/d/1uDjGZcWln07jb0dL60Yuz_33Ck78DQXF/view?usp=drive_link)

![MasterHead](https://img.freepik.com/free-vector/car-showroom-center-with-autos-exhibition-inside-automobile-dealership-store-shop-interior-new-modern-vehicles-models-demonstration-sale-trading_575670-1511.jpg?w=826&t=st=1699422007~exp=1699422607~hmac=3b2f5d6b9a8a9a9d789b029b73ea0744c0dfebbf1a78a9a89b775c6167ee943e)

<font size="1">Image Courtesy: https://img.freepik.com/free-vector/car-showroom-center-with-autos-exhibition-inside-automobile-dealership-store-shop-interior-new-modern-vehicles-models-demonstration-sale-trading_575670-1511.jpg?w=826&t=st=1699422007~exp=1699422607~hmac=3b2f5d6b9a8a9a9d789b029b73ea0744c0dfebbf1a78a9a89b775c6167ee943e</font>

Click on the following link to checkout the colab file.
- [Colab](https://colab.research.google.com/drive/1n4thlpzHBQJe5JXhfyZ6SpRu20KDksWJ?usp=sharing)


---

## Problem Statement

**Project Overview:**

In the automotive industry, determining the price of a car involves various factors, such as brand reputation, car features, horsepower, and fuel efficiency. Car price prediction is a crucial application of machine learning. This project is designed to help you learn how to build a model for car price prediction.

**Key Objectives:**

- Explore the factors affecting car prices.
- Create a machine learning model to predict car prices.
- Gain valuable experience in the field of machine learning and automotive pricing.

---

## Project Summary

**Objective:** Develop a machine learning model to predict car prices based on various influencing factors.

**Why Car Price Prediction?** Car prices are influenced by numerous variables, including brand reputation, features, horsepower, and fuel efficiency. Machine learning models can provide accurate price predictions.

**Key Tasks:**

1. **Data Collection:** Gather data on various car attributes and their corresponding prices.
2. **Data Preprocessing:** Clean, transform, and prepare the data for modeling.
3. **Feature Engineering:** Identify the most important features for price prediction.
4. **Model Building:** Create a machine learning model capable of predicting car prices.
5. **Model Evaluation:** Assess the model's accuracy and performance using appropriate metrics.
6. **Deployment:** Make the trained model available for car price predictions.

**Benefits:** By completing this project, we'll gain valuable insights into machine learning, data analysis, and the automotive industry. We'll also have a functional car price prediction model that can be useful for future car pricing decisions.

---

## Results

I have selected R2 score as the primary evaluation metric for the Car Price Prediction model. And after removing the overfitted models which have MSE, R2 score, Adjusted R2 score for train as 100% and also have negative accuracy value, we get the final list:

| Sl. No. | Regression Model      |   R2 Train (%) |   R2 Test (%) |
|:--------|:--------------------------|---------------:|--------------:|
|    1    | Linear Regression         |       64.21  |      49.24 |
|    2    | Linear Regression tuned       |       64.21  |      49.24 |
|    3    | Lasso Regression tuned       |       63.62 |      49.57 |
|    4    | Ridge Regression         |       64.19 |      49.36 |
|    5    | Ridge Regression tuned        |       63.92 |      50.22 |
|    6    | Decision Tree tuned         |       76.00 |      70.37 |
|    7    | Random Forest         |       98.61 |      93.05 |
|    8    | Random Forest tuned        |       77.10 |      73.71 |
|    9    | Gradient Boosting Regressor         |       98.78 |      90.47 |
|    10    | Gradient Boosting Regressor tuned        |       96.11 |      88.24 |

## Conclusion

This project explores the automotive industry's intricate dynamics, aiming to predict car prices with machine learning. By analyzing various factors such as fuel type, seller type, and transmission, we uncover valuable insights and select a robust model for accurate price prediction.

**Key Insights:**

- The 'city' model is the top-selling car, followed by 'corolla altis,' 'verna,' 'fortuner,' and 'brio,' providing a snapshot of popular car models in the market.

- The year 2015 saw the highest number of car purchases, making it the most favored year for buying cars, followed by 2016 and 2014.

- 'Petrol' is the predominant fuel type for cars in the dataset, surpassing 'Diesel' and 'CNG,' indicating fuel preference among buyers.

- The majority of cars are sold through dealers, underscoring the role of dealerships in the automotive market.

- 'Manual' transmission cars significantly outnumber 'Automatic' transmission cars, showcasing consumer transmission preferences.

- 'First Owner' cars generally command higher 'Selling_Price,' while 'Second' or 'Third Owner' cars often have lower prices.

- 'Diesel' cars tend to have higher 'Selling_Price' compared to 'Petrol' or 'CNG' vehicles, emphasizing the influence of fuel type on car pricing.

- 'Dealer' sellers usually ask for higher prices than 'Individual' sellers, revealing the impact of seller type on prices.

- 'Automatic' transmission cars typically have higher prices than their 'Manual' counterparts, reflecting consumer preferences.

- 'Owner' count plays a role in car pricing, with 'First Owner' cars being more expensive than 'Second' or 'Third Owner' cars.

- The relationship between driven kilometers and 'Selling_Price' is negative, suggesting that cars with fewer kilometers tend to have higher selling prices.

- Various machine learning models were assessed, with the Random Forest model being chosen for car price prediction due to its robust performance.

- The project used the R2 score as the primary evaluation metric to assess model accuracy.

- The Random Forest model achieved impressive accuracy with 98% training accuracy and 93% testing accuracy, making it a suitable choice for car price prediction.

The insights provide a holistic understanding of the factors influencing car prices, both from exploratory data analysis and machine learning model perspectives. The Random Forest model's accuracy underscores its potential for practical applications in the automotive market.

This project has not only equipped us with valuable data science skills but has also deepened our understanding of car pricing, making it a significant step in the field of data science and machine learning.

---

## Author

- [Arindam Paul](https://www.linkedin.com/in/arindam-paul-19a085187/)

---

## Reference
 - [Oasis Infobyte](https://oasisinfobyte.com/)
