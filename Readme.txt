This notebook contains several analysis made over the dataset “London bike sharing dataset”, which is available in Kaggle: https://www.kaggle.com/hmavrodiev/london-bike-sharing-dataset . The idea is to address the problem of predicting bike sharing demand in the city of London.

The code implemented for the classifiers is based on the code written by Hristo Mavrodiev. The actual contribution of this notebook is in the analysis of the data, particularly in finding that positive outliers correspond to two specific dates, both of them caused by a shut down of the underground. So that, records from both dates can be removed before training the models.

There are some notes in the .ipynb that explain the overall analysis made on the data, as well as the models employed.