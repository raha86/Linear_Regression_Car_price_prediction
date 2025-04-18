# Linear_Regression_Car_price_prediction

## Dataset link:
https://drive.google.com/file/d/1JHPaqHG8sZIzkpvIW0RC7DdH864lec7N/view?usp=sharing

## Problem Statement
A Chinese automobile company Geely Auto aspires to enter the US market by setting up their manufacturing unit there and producing cars locally to give competition to their US and European counterparts.

They have contracted an automobile consulting company to understand the factors on which the pricing of cars depends. Specifically, they want to understand the factors affecting the pricing of cars in the American market, since those may be very different from the Chinese market. The company wants to know:

Which variables are significant in predicting the price of a car How well those variables describe the price of a car Based on various market surveys, the consulting firm has gathered a large data set of different types of cars across the America market.

## Business Goal
We are required to model the price of cars with the available independent variables. It will be used by the management to understand how exactly the prices vary with the independent variables. They can accordingly manipulate the design of the cars, the business strategy etc. to meet certain price levels. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

# Steps Performed: 
### 1. Performed exploratory data analysis to find out relation between independent and dependent variables.
* Checked for null values.
* Checked for duplicates.
* Performed data manipulation. (converted 'doornumbers', 'cylindernumbers' column values to 'int64' from 'object')
  
### 2. Performed label encoding.

### 3. Performed Feature selection for data modelling.
* Used <b>correlation matrix and heatmap</b> to select required feature.
  
### 4. Performed data preprocessing.
* Normalizing the features so that the samples will have the same mean and standard deviation. Used standard scaler.

### 5. Model Building.

### 6. Model Evaluation.
* Used <b>R2-Score</b> to evaluate model performance.
* Achieved: R2-Score 0.899 (~90%).

### 7. Visual Representation.
![image](https://github.com/user-attachments/assets/bf2d1677-d0b3-4255-964a-172065f937c3)



