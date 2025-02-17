# machine-learning-demo

Nos critères de classification :
-> Metrics
    - Log loss y=0,1 ; -(ylog(p) + (1-y)log(p))
    - Brier score somme de (p-y)² : on compare chaque val de y à la probabilité
    - Accuracy
-> Si régression (au lieu de classification) :
- MSE
- R² ; R² ajusté

Tout ça c'est des métriques qu'on peut avoir avec des randomforest. Faire au moins des randomforest, sinon essayer de faire du gradient boosting, etc.
Avant tout, faire des stats descriptives des variables. Avec histogrames pour les vars quantitatives, des boxplots (l'âge entre les femmes et les hommes / fumeurs non fimeurs...). Pour montrer les trucs significatifs de ce jeu de données la. Ou justment montrer que y'a pas de pbs dans le jeu de données. Test d'indépendance du chi² (variables qualitatives) ou student pour quantitatives.

Rajouter ce qu'on aime si on trouve des trucs cools aussi.
Montrer qu'on comprend un minimum ce que l'on fait.


Faire un jupyter notebook ou un rmarkdown
Que ça soit visuel pour présenter à l'oral. Des slides ou utiliser le rapport rmarkdown en tant que support ou défiler le jupyter notebook.

