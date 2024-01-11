# UC_wildfire_forecasting

This repository if for the course Urban computing at the Leiden University - LIACS      

### Repository structure
the *\models* directory holds the three trained models from the ConvLSTM architecture.      
the **STAR.ipynb** holds the following:     

        Implementation of the Spatio-temporal Autoregressive model.     
        Creation of the gifs that can be found in the \figures folder.      
        Some more data visualisation.

The **Data exploration and neural net implementation.ipynb** notebook holds the following:      

        Data exploration of the Burned area patch dataset       
        Data exploration of the Burned area pixel dataset       
        Visualisation of the **Burned area pixel** dataset      
        Data pre-processing, model architecture and training of the ConvLSTM models     
        Visualisations of the results of the trained models.

Make sure to import all necessary packages using `pip install -r requirements.txt`before running anything.

Also, the datasets can be downloaded here:      

        https://climate.esa.int/es/odp/#/project/fire

Be warned, it is a lot of data and it takes a long time to download everything. The notebooks will explain the folder structure for the dataset creation but this could also be adapted by the user to fit their needs of course.