# krafthack-2022-open
This is a repository containing all of the code and data for Krafthack 2022.

### Download the data
* The data is located here > https://krafthack.azurewebsites.net/dataset
* Users need to create a folder called ```data``` within the directory and save the **parquet files called ```input_dataset-1.parquet``` and ```input_dataset-2.parquet```** to this folder


### Notebooks
* ```01_data_exploration_preparation.ipynb``` - use this notebook to explore and prepare the data (**```TODO```**: move a lot of the data prep stuff from the 2nd notebook like NaN removal and feature generation to this notebook)
* ```02_model_training.ipynb``` - use this notebook to train models for linear regression, gradient boosting regression, and LSTMs
* ```03_model_evaluation.ipynb``` - use this notebook to compare model output
