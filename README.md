# Predicting the daily sales of Rossmann Stores

Rossmann operates over 3,000 drug stores in 7 European countries. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied.

To know more about the dataset, check https://www.kaggle.com/c/rossmann-store-sales

As the dataset lacked in certain cases, like providing information about the location and weather, information about the location was inferred based on holidays, and knowing the location, a weather dataset was merged accordingly.

link to the datasets used: https://drive.google.com/file/d/13WDkahmNbQSx_CwWo7fGH_92u5uiioO3/view?usp=sharing

This project is split into 2 phases:

### Phase 01
Phase 01 of the project dealt with Data Cleaning, EDA and feature Engineering.

### Phase 02
Phase 02 of the project dealt with using various ML models (Multi Linear Regression, Lasso Regression, Gradient Boosted Trees, RNN) to predict Sales of the Rossmann Stores.
Among all the models used the gradient boosted trees models (LGBM model) shows most promise, with score of 98%

## Run the project locally

### Requirements
- Python 3.x 
- Jupyter
- Required ML libraries & visualisation libraries (scikit-learn, keras, tenserflow, numpy, pandas, seaborn, matplotlib) 

### To run the project
- Download the ipython files present under **code** folder of the repo
- Make sure to change the paths used for reading the datasets accordingly
- Run all the cells of the jupyter notebook

Note that the first ipython file creates 3 .csv files namely, location.csv, cleaned_weather.csv & final_Rossmann.csv.
final_Rossmann.csv is used as input for the second ipython file, alternatively, you can download this file from the provided drive link too.

## Run the project on Colab

- Rossmann_Stores_cleaning_EDA_feature_engg.ipynb on [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1DsQ7wRGrX66ma65QItQb7HptiVo3wBPY?usp=sharing) 
- predict_RossmannSales.ipynb on [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1mgUAhohqbsJm9oivW5QH2e0Lpy7_XpDw?usp=sharing)








