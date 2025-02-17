# machine-learning-demo

## Analyzing the dataset

First things first, we need to understand the dataset we are working with.

- With histograms for quantitative variables, boxplots to show the presence or absence of significant relationships between variables in this dataset.
- With chi-squared tests for qualitative variables, and student tests for quantitative variables, again to study the dataset for any significant relationships.
- We will determine confidence intervals, divide the dataset into training and testing sets, and anything else of interest in the dataset.

## Predicting the target variable

The final goal is to predict the target variable, which is wine quality. We will use machine learning algorithms to predict this target variable.


Nos critères de classification :
-> Metrics
    - Log loss y=0,1 ; -(ylog(p) + (1-y)log(p))
    - Brier score somme de (p-y)² : on compare chaque val de y à la probabilité
    - Accuracy
-> Si régression (au lieu de classification) :
- MSE
- R² ; R² ajusté

Tout ça c'est des métriques qu'on peut avoir avec des randomforest. Faire au moins des randomforest, sinon essayer de faire du gradient boosting, etc.

Rajouter ce qu'on aime si on trouve des trucs cools aussi.
Montrer qu'on comprend un minimum ce que l'on fait.


Faire un jupyter notebook ou un rmarkdown
Que ça soit visuel pour présenter à l'oral. Des slides ou utiliser le rapport rmarkdown en tant que support ou défiler le jupyter notebook.

