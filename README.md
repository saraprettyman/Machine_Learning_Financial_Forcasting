# Machine Learning Financial Forcasting 
This is a group project for Introduction to Machine Learning (CS 4320). 


## Project Overview
**Step 1** [Preprocessing](https://github.com/saraprettyman/Machine_Learning_Financial_Forcasting/blob/master/preprocessing.ipynb)

## Data
### Source
The data used in this project comes from a Kaggle Competition titled [*Store Sales - Time Series Forecasting*](https://www.kaggle.com/competitions/store-sales-time-series-forecasting/overview). The data was exported on 10/7/2023. 

### Variables
The training varaibles are as follow: 

|Variable|Type|Description
|---|:---:|---|
|store_nbr|Numeric|Identifies the store at which the products are sold.
|date |Object | Identifies when the sales took place. 
|family| Object | Identifies the type of product sold.
|sales|Numeric| Represents the total sales for a product family at a specific store on a given date. Fractional values are possible since products can be sold in fractional units (for instance, 1.5 kg of cheese as opposed to 1 bag of chips).
|onpromotion| Numeric | Represents the total number of items in a product family that were being promoted at a store on a given date.

Other variables are used from different csv files during this project. For more information, click [here](https://www.kaggle.com/competitions/store-sales-time-series-forecasting/data)