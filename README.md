# energyPredictor
https://www.kaggle.com/c/ashrae-energy-prediction/data


### Notebook folder
The Notebook folder contains all the notebooks necessary to run the prediction.
First, run the building metadata preprocessing and weather preprocessing notebooks. Next, the Train and Test Preprocessing.
Finally, choose one of the algorithms to train a model and make predictions.
Make sure to update the import paths.


### CSV folder
The CSV folder contains the csv files for preprocessed building metadata as well as the weather data.
Unforunately, the train and test preprocessed csv's are too large (even when compressed) to be uploaded to github.
However, running the provided notebooks will provide the csv's.


#### DataFrame size reduction

We experimented with dataframe reduction at various places in different notebooks.
It was used to preprocess data, or before fitting a model.
The code for size reduction can be found in the 'Predicting with linear SVR' notebook.
