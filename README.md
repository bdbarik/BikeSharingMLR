# Bike Sharing Demand Prediction

> A multiple linear regression project to identify key factors influencing daily bike rental demand.

## Table of Contents

* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

## General Information

* This project builds a **multiple linear regression model** to predict the daily bike demand (`cnt`) for a US-based bike-sharing company, **BoomBikes**.
* The background of the project is rooted in a **post-pandemic recovery scenario**, where BoomBikes aims to understand demand patterns to improve operational and strategic decisions.
* The business problem: **Identify significant variables driving bike demand** and determine how well these variables explain demand variations.
* The dataset used is **`day.csv`**, containing daily aggregated bike rental counts along with weather, seasonal, and temporal features.
* Key steps performed include:

  * Data cleaning
  * Categorical conversion & dummy encoding
  * Train-test split
  * VIF analysis to detect multicollinearity
  * Backward elimination using p-values
  * Final regression model building
  * Model evaluation through residual analysis and R-squared metrics

## Conclusions

* **Temperature** is one of the strongest predictors of bike demand, positively affecting rental counts.
* **Seasonality**, particularly **winter, summer, and fall months**, significantly increases demand compared to the baseline.
* **Weather conditions**, such as cloudy or rainy weather, reduce bike rental demand.
* **Year (`yr`)** shows that overall demand increased substantially from 2018 to 2019, indicating growing adoption of bike-sharing services.
* The final model achieved a **test R-squared of ~0.84**, demonstrating strong explanatory power and good generalization.

## Technologies Used

* Python 3.x
* pandas
* numpy
* statsmodels
* scikit-learn
* matplotlib

## Acknowledgements

* This project was inspired by a business case study on post-pandemic demand forecasting.
* Dataset provided as part of a machine learning assignment.
* Modeling approach informed by best practices in linear regression and multicollinearity handling.

## Contact

Created by [@bdbarik] - feel free to contact me!
