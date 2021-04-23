# BT4222
BT4222 Group 13
Members: Nicole Png, Toh Jia Xuan, Vicki Yew, Wong Zheng Yi, Chang Wei Sheng

# Project Background 
In this project, we aim to predict prices of resale property in Singapore. 
Various Machine and Deep Learning techniques were explored, with our final predictive model being XGBoost.
Features such as neighbouring amenities, details of properties and sentiment of the properties' will be taken into account as part of the modelling process. 

# Project Motivation
A research by the NUS Institute of Real Estate and Urban Studies has raised concerns that buyers in Singapore are overpaying for property, especially freehold ones. 
Thus, through this project, we seek to accurately predict the prices that properties should warrant. This helps to ensure that prospective buyers are being offered a fair price for their prospective properties and are not overpaying.

# 1. Data 
Datasets are available in the 'Data' Folder under the main branch. 
To successfully run all codes, these data would need to be downloaded. Their respective file paths would then be needed to be altered in the relevant Jupyter notebooks in the other folders. 

# 2. Data Cleaning and Exploratory Data Analysis 
Notebooks on data cleaning (such as dataframe manipulation and merging of datasets) and Exploratory Data Analysis can be found in the 'Preprocessing' Folder under the main branch. 

# 3. Sentiment Analysis 
Sentiment Analysis of each neighbourhood in Singapore can be found in the 'Sentiment_Analysis' Folder under the main branch.
Sentiments were obtained through scraping of websites such as Reddit and HardWareZone. 

# 4. Latent Dirichlet Allocation (LDA)
Results for the LDA Tuning can be found in the 'Lda Tuning Results' folder under the main branch.

# 5. Modelling 
Notebooks from the modelling process can be found in the 'Models' Folder under the main branch. 
This folder includes:
- OLS & Polynomial Regression Models (OLS & Polynomial Regression.ipynb)
- Decision Tree & Random Forest Models ([Final] Random Forest Final psf v2.ipynb)
- XGBoost & LightGBM Models (Final Model will be XGBoost) ([Final] LightGBM+XGBoost_SHAP_v3.ipynb)
- Ensemble Learning (Stacking) Model ([Final] Ensemble.ipynb)
- Sequential Deep Learning Model ([Final] Sequential Model Deep Learning.ipynb)
- The saved final model (xgb_model.sav) (xgb_model.sav)
- A function Model Prediction notebook for price prediction ([Final] Model_Prediction_FeatureCross.ipynb)

For the functional Model Prediction notebook ('[Final] Model_Prediction_FeatureCross.ipynb'), 
ensure that (1) the relevant datasets and saved final model are downloaded, and that (2) their filepaths are altered accordingly in the code cells. 
When running the code cells, users will be prompted to key in details of the property whom prices they would like to predict. After keying in the relevant details, the predicted price per square foot of the property would be shown in the last code cell. 
