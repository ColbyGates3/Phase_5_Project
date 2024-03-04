# DS-Capstone
Flatiron School Data Science Project - Phase 5

## Overview
* Purpose: Create a ML model to predict Indian Rice Yield Prediction on novel features
* Source of data: Kaggle [Data](https://www.kaggle.com/datasets/sudhanshu2198/crop-yield-prediction-hachathon/data?select=Train.csv) 
* Data: Rice yields from ~4000 farms (44 features)

 
# Presentation
Presentation: [Link](https://docs.google.com/presentation/d/1AiqCMS01KniJ_c9b4oOcS4zDexuqxy_VaA3dzG9Akag/edit#slide=id.p)

# Repository Navigation
This Github Repository contains 1  main folder named Notebooks. The other images folder just contains images for this document. The Notebooks folder has 2  notebooks in it. The first of these notebooks is titled Rice_Yield_EDA_Preproccessing and contains all of my data cleaning and preprocessing steps. It is important to run this notebook first as cleaned data files are created which the Modeling notebook then calls. The next notebook is titled Modeling and contains all of the modeling steped as well as evaluation for each model.

## Data Analysis & Recommendations
<img width="927" alt="Screenshot 2024-03-04 at 9 38 32 AM" src="https://github.com/ColbyGates3/Phase_5_Project/assets/146360524/9e7e3ca0-610e-48fe-834f-4e4db7cb4dc1">


<img width="792" alt="Screenshot 2024-03-04 at 9 33 26 AM" src="https://github.com/ColbyGates3/Phase_5_Project/assets/146360524/b6e79dca-1374-42e7-b92d-b07ec8b94bcd">

<img width="1243" alt="Screenshot 2024-03-02 at 2 59 20 PM" src="https://github.com/ColbyGates3/Phase_5_Project/assets/146360524/a16f46db-36d5-4e79-8b82-c1948fc87563">



* Best Model was a CatBoost Model with a MAE of 179 Yield/Acre



Our recommendations are the following:
* For Accuracy use a CatBoost model
* Most important features to consider are length of residue, crop tillage depth and hours of irrigation
* inherently challening problem. May be hard to get more accurate with novel data





