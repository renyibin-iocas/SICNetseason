# SICNetseason
## Seasonal sea ice prediction model based on transformer.

The core codes of the model are in the model_utils folders. The jupyter file "SICNet_season_training.ipynb" contains the flow of loading data, defining a model, and training the model. The "SICNet_season_evaluating.ipynb" includes evaluating the trained model and drawing the ACC/BACC result. The training and testing data are in the Data/Data.zip file and can be loaded for training and evaluation of the model. The well-trained models are in the path of Result/Model_SICNet/. Because the well-trained model is too large (10GB), it cannot be supported by the github. The satellite-observed sea ice concentration is obtained from the following site https://nsidc.org/data/NSIDC-0081/versions/1. The reanalysis of sea ice thickness data is open access (http://psc.apl.uw.edu/research/projects/arctic-sea-ice-volume-anomaly/data/model_grid). The seasonal predictions of SEAS5 are available from the ECMWF (https://cds.climate.copernicus.eu/cdsapp#!/dataset/seasonal monthly-single-levels?tab=form).
