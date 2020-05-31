# ErdosBootCampSIGproject
Final project for Erdos Institute Code boot camp. This is for the challenge issues by SIG to create an over/under predictor for a given NBA game

The data gathering notebooks detail how we created our NBA dataframe. They are enumerated in approximate order of creation, but they might overlap at parts. 

The other notebooks detail the methods we used to try and create a decent over/under model. The best methods are detailed in the FastaiTabular78Acc.ipynb or the EnsembleModel92AUC72Acc.ipynb notebooks, both of which predicted the correct class (Over/Under) well (72% for h2o clustering and 79% for fastai deep learning)

Included here are the final dataframes with all varaibles included and the specialized ones created for ML notebooks. 

Also included is the .pkl file of the trained fastai model. This can be easily loaded to make predictions as is demonstrated in Fastai_in_production.ipynb
