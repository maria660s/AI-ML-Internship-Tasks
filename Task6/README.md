# House Price Prediction

## Overview
This project predicts house prices using various property features such as area, number of bedrooms, bathrooms, stories, and other amenities. The goal is to build a regression model that can estimate house prices based on these features.

## Dataset
The dataset contains the following columns:

- `price`: Target variable (house price)
- `area`: Size of the house in square feet
- `bedrooms`: Number of bedrooms
- `bathrooms`: Number of bathrooms
- `stories`: Number of stories in the house
- `mainroad`: Whether the house is near the main road (yes/no)
- `guestroom`: Availability of a guest room (yes/no)
- `basement`: Presence of basement (yes/no)
- `hotwaterheating`: Hot water heating system (yes/no)
- `airconditioning`: Air conditioning availability (yes/no)
- `parking`: Number of parking spaces
- `prefarea`: Whether the house is in a preferred area (yes/no)
- `furnishingstatus`: Furnishing status of the house (furnished, semi-furnished, unfurnished)

## Steps Performed

1. **Data Loading and Exploration**  
   Loaded the dataset and checked for missing values and data types.

2. **Data Preprocessing**  
   - Filled missing values (if any).  
   - Converted categorical `yes`/`no` features to binary 1/0.  
   - One-hot encoded multi-class categorical features like `furnishingstatus`.  
   - Standardized numeric features such as `area` and `bedrooms`.

3. **Model Training**  
   Used a pipeline to preprocess data and train a regression model (Linear Regression by default).

4. **Evaluation**  
   Evaluated the model using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

5. **Visualization**  
   Visualized the predicted house prices vs. actual prices to assess model performance.

## How to Run

1. Ensure all dependencies are installed:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
