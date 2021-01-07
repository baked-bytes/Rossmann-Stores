# Rossmann Stores

Rossmann operates over 3,000 drug stores in 7 European countries. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied.

To know more about the dataset, check https://www.kaggle.com/c/rossmann-store-sales

As the dataset lacked in certain cases, like providing information about the location and weather, information about the location was inferred based on holidays, and knowing the location, a weather dataset was merged accordingly.

link to the datasets used: https://drive.google.com/file/d/13WDkahmNbQSx_CwWo7fGH_92u5uiioO3/view?usp=sharing

This project is split into 3 phases:

### Phase 01
Phase 01 of the project dealt with Data Cleaning, EDA and feature Engineering.

### Phase 02
Phase 02 of the project dealt with using various ML models (Multi Linear Regression, Lasso Regression, Gradient Boosted Trees, RNN) to predict Sales of the Rossmann Stores.
Among all the models used the gradient boosted trees models (LGBM model) shows most promise, with score of 98%

### Phase 03:
Phase 03 dealt with using all the data inferred, from the previous phases, to create a simple business dashboard using tableau.

## Run the project locally

### Requirements
- Python 3.x 
- Jupyter
- Required ML libraries & visualisation libraries (scikit-learn, keras, tenserflow, numpy, pandas, seaborn, matplotlib) 
- Tableau Desktop

##### Ipython files
- Download the ipython files present under **code** folder of the repo
- Make sure to change the paths used for reading the datasets accordingly
- Run all the cells of the jupyter notebook

Note that the first ipython file creates 3 .csv files namely, location.csv, cleaned_weather.csv & final_Rossmann.csv.
final_Rossmann.csv is used as input for the second ipython file, alternatively, you can download this file from the provided drive link too.

## Run the project on Colab

- Rossmann_Stores_cleaning_EDA_feature_engg.ipynb on [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1DsQ7wRGrX66ma65QItQb7HptiVo3wBPY?usp=sharing) 
- predict_RossmannSales.ipynb on [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1mgUAhohqbsJm9oivW5QH2e0Lpy7_XpDw?usp=sharing)

## Run tableau playbook locally
- Download the tableau playbook & final_RossmannSales.csv from the provided drive link.
- Establish a live data source connection & run

Alternatively, you can check it out on Tableau Online


[![image](https://user-images.githubusercontent.com/44095548/103937966-904a8080-514f-11eb-8962-4c3553b1e1b4.png)](https://prod-apnortheast-a.online.tableau.com/t/rossmannstores/views/Rossmann_project/ExecutiveOverview/nayak.amit.blr@gmail.com/55b376ad-20d8-48c6-8596-902ad5cebf6c?:display_count=n&:showVizHome=n&:origin=viz_share_link)


[![image](https://user-images.githubusercontent.com/44095548/103938578-79f0f480-5150-11eb-978a-528a84568080.png)](https://prod-apnortheast-a.online.tableau.com/t/rossmannstores/views/Rossmann_project/AnalyticOverview/nayak.amit.blr@gmail.com/b98acdbc-ecae-4c31-9ccc-9248337f0c2e?:display_count=n&:showVizHome=n&:origin=viz_share_link)


[![image](https://user-images.githubusercontent.com/44095548/103938803-d3592380-5150-11eb-9a4c-5d75d034cb78.png)](https://prod-apnortheast-a.online.tableau.com/t/rossmannstores/views/Rossmann_project/ManagerOverview?:showAppBanner=false&:display_count=n&:showVizHome=n&:origin=viz_share_link)






