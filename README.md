# machine-learning-demo

## Analyzing the dataset

First things first, we need to understand the dataset we are working with.

- With histograms for quantitative variables, boxplots to show the presence or absence of significant relationships between variables in this dataset.
- With chi-squared tests for qualitative variables, and student tests for quantitative variables, again to study the dataset for any significant relationships.
- We will determine confidence intervals, divide the dataset into training and testing sets, and anything else of interest in the dataset.

## Predicting the target variable

The final goal is to predict the target variable, which is wine quality. We will use machine learning algorithms to predict this target variable.  
For each method we use, we will explain our understanding of how it works, its results, and how they compare to other methods.

We will use the following prediction algorithms:

- Random Forest
- (Gradient Boosting)

We will use the following classification criteria:

- Log loss
- Brier score
- Accuracy

For regression, we will use:

- MSE
- R²

These are all metrics that we can get with random forests. We will at least use random forests, but we may also try to use gradient boosting, or other methods if we have time.

## Report presentation

We will present our work in an Rmarkdown report. We will use this report as a support for our oral presentation, including visualizations. We may also use slides.


Some math for understanding stuff:
Log loss: y=0,1 ; -(ylog(p) + (1-y)log(p))
Brier score: sum of (p-y)² : each prediction is a probability, and we compare it to the actual value.


Chose à faire : classification randomforest en classant en 2 catégories : 0-5 et 6-10 pour les vins bons et mauvais

rég logi
couper en deux de 05 et 6 10
randomforest bien pour des trucs ordinaux
10 régressions logistiques : pour prédire chaque qualité de vin ; puis on regarde la qualité qui a la plus forte proba
