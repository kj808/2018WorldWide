# WorldWide

Description: Many products are sold; however, depending on the season, some products are in more demand than others. Given a data set with order dates and demand quanitity, can the future demand be forecasted?

Location: Data Science Graduate Course at KU 

Dates: Oct 14, 2018

## Goal
* Predict future demand of products

## Data
* [Historical Product Demand](https://www.kaggle.com/felixzhao/productdemandforecasting). Dataset including the order product, date needed, the number of orders

## Techniques Used
* I performed data rangling on the two data sets (i.e., normalized features, combined data sets, removing unrelevant entries, randomizing entries)
* I split data into training/testing/validation for 80/10/10
* Applied two models: Gradient Boosting and Random Forests

## Results
Many orders are placed based on supply and demand. By using gradient boosting and random forests, one can forecast the demand. However, with a R squared score under 0.56 for both models, this does not prove highly efficient. The lack of determined variance fit could be due to the lack of features. Certain weather conditions can also affect orders as well as warehouse reputations. By only using date information and order information as well as source, these two models do not forecast as well.

## Repository Contents

| Directory | Description |
| --- | ----------- |
| Data | Contains all of the datasets used in this project. |
| Libraries | If libraries are used, the exact distribution will be located here. Includes library, library name, and library version. |
| Models | Models generated for the project such as machine learning models. |
| Notebooks | Notebooks used for visualing the data. |
| Reports | The resulting reports on this project. |
| Src | Source scripts and other helper files located here. |


