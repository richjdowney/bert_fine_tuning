# Fine Tuning a BERT model to predict movie genre

Applies fine tuning with a custom classification head to a pre-trained Distilibert model.

The repo contains 3 notebooks:

1. Import and explore:  Imports the data, checks for missing values and produces some plots of the features
2. Build model:  Builds a simple model to predict movie genre from description and evaluates errors on a test set
3. Build model multi feature:  Adds an additional categorical feature that is embedded and two numerical features along with the movie description embedding and retrains
