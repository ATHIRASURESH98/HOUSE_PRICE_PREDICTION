# **HOUSE PRICE PREDICTION**
This repository contains code for predicting the house price of houses in Bengaluru using some machine learning models in python.  The dataset used in this analysis is sourced from the kaggle website.
## **Requirements**
To run this code, you need to have the following installed:

- Python 3.x
- Pandas
- Jupyter Notebook
## Data
The data used in this analysis is sourced from the Kaggle website. It contains the following fields:
- area_type: Type of the area where the house was locating
- availability: The date from where the house is available
- location: The name of place where house is located
- size:  Size of the house
- society: The name of society where the house is located
- total_sqft: The totak square feet of house
- bath: The number of bathrooms
- balcony:  The number of balcony
- price: Total price of the house
## Analysis
The price prediction using this data is done by Machine Learning in Python.  The code for the analysis is provided in the Jupyter Notebook file Home_price_prediction.ipynb.
- In this prediction using GridSearchCV we find that linear model is the best fit model.
- For the prediction using linear model we use following columns:
    - location
    - sqft
    - bath
    - bhk
## **Usage**
To run the code, you can follow these steps:

1. Clone the repository
2. Install the required libraries using pip install -r requirements.txt
3. Launch Jupyter Notebook using jupyter notebook
4. Open the file Home_price_prediction.ipynb
5. Run the code cells in the notebook

## **Conclusion**
This prediction help to predict price of house in bengaluru city. This code can be further modified and extended to perform more acurate prediction by adding more values and columns




