# SICNetseason
## Seasonal sea ice prediction model based on transformer.

1. The core codes of the model are in the model_utils folders. The jupyter file "SICNet_season_training.ipynb" contains the flow of loading data, defining a model, and training the model. 
2. The "SICNet_season_evaluating.ipynb" includes evaluating the trained model and drawing the ACC/BACC result. 
3. The training and testing data are in the Data/Data.zip file and can be loaded for training and evaluation of the model. The files "SIC_1979_2020_Jan_May_96.npy", "SIT_1979_2020_Jan_May_96.npy", "SIC_climate_mean_96.npy", and "mask_96.npy" are input data for model training. The "Output data" file contains the predicted results output by our model, "Predicted_SIC_output.npy". The "Ground_SIC_output.npy" in this file is the ground truth from NSIDC.
4. The well-trained models are in the path of Result/Model_SICNet/. They are uploaded seperately in the Zenodo.
