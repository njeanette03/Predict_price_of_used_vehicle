# Predict the Price of a Used Vehicle

## Overview
This dataset is a valuable resource for automotive enthusiasts, buyers, and researchers interested in analyzing trends, making informed purchasing decisions or conducting studies related to the automotive industry and consumer preferences.  

In this notebook, I predict the price of a used vehicle as part of a KaggleX competition. Submissions are scored on the root mean squared error. For each id in the test set, the price of the car must be predicted.

## Dataset

The dataset for this competition (both train and test) was generated from a deep learning model fine-tuned on the [Used Car Price Prediction Dataset](https://www.kaggle.com/datasets/taeefnajib/used-car-price-prediction-dataset) dataset. Feature distributions are close to, but not exactly the same, as the original.

- id : The id associated with the car.
- brand : Brand or company name.
- model : Specific model.
- model_year : Year of manufacturing.
- milage : The mileage of each vehicle.
- fuel_type : Type of fuel the vehicles run on. (gasoline, diesel, electric, or hybrid)
- engine : Type of engine.
- transmission : The transmission type. (Automatic / Manual)
- ext_col : Exterior color.
- int_col : Interior color.
- accident : Accident history.
- clean_title : A clean title tells you a vehicle has never been declared a total loss.
- price : Price listed by the seller.

## Files
- Predict_price_of_used_vehicle.ipynb - Jupiter Notebook with code
- train.csv - the training dataset
- test.csv - the test dataset
- sample_submission.csv - a sample submission file in the correct format

## Approach

1. The dataset was downloaded, explored, and analyzed with a focus on identifying its features and characteristics.
2. An in-depth exploratory data analysis was conducted, data was preprocessed by dropping unnecessary columns and removing outliers, along with feature engineer as necessary and label encoding for categorical variables.
3. Different models are then trained and evaluated on the given dataset and predictions.
4. A final model after multiple revised iterations is selected.


## Acknowledgements
Kaggle is hosting this competition for the machine learning community to use for fun and practice. 
