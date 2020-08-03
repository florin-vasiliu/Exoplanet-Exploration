# Machine Learning - Exoplanet exploration

## Background

<img src=images/exoplanets.jpg>
Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

This project is concerned with determining a machine learning model that processes several <a href ='https://exoplanetarchive.ipac.caltech.edu/docs/API_kepcandidate_columns.html'>features</a> recorded by the Kepler Space Observatory, and predicts with reasonable accuracy the presence of a planet.

## Project development

The <a href='https://github.com/florin-vasiliu/machine-learning-challenge/blob/master/data/exoplanet_data.csv'>dataset</a> consists of a discrete label column, and several features together with their uncertainities, that will be used to build the model. 

Since the labels are discrete values, the models used for prediction were classification models, namely <a href='https://github.com/florin-vasiliu/machine-learning-challenge/blob/master/Recursive%20Feature%20Elimination%2BK%20Nearest%20Neighbor.ipynb'>K Nearest Neighbors</a> and <a href='https://github.com/florin-vasiliu/machine-learning-challenge/blob/master/Support%20Vector%20Machine.ipynb'>Support Vector Machine</a>.

The steps for the models' development are described in each .ipynb file, and the best accuracy among the 2 models was obtained on the K Nearest Neighbors classification model (about 85% accuracy using 13 nearest neighbors). The result of the model was finaly saved in the <a href='https://github.com/florin-vasiliu/machine-learning-challenge/blob/master/Florin_Vasiliu.sav'>Florin_Vasiliu.sav<a> file.
