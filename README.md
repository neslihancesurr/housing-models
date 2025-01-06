# Housing price models

#### Data
- novemberdata.json: the raw data scraped from HepsiEmlak. includes around 25.000 apartment listings in İstanbul.
- cleaned_data_model: the data after the application of data_cleaning file.

#### Cleaning and Correlations
- emlak-data-cleaning: switching to numerical values, getting rid of outliers
- emlak-correlations: visualizations of relationships between features

#### Models
- emlak-linear: a linear regression model built with scikit-learn (K-fold cross-validation + MAE, NAE + price prediction example)
- emlak-polynomial: a polynomial regression model built with scikit-learn (K-fold cross-validation + MAE, NAE + price prediction example)
- emlak-randomforest: a random forest model built with scikit-learn (K-fold cross-validation + MAE, NAE + price prediction example)
