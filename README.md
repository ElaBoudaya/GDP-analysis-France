# GDP-analysis-France
e projet explore l’évolution du PIB de la France en utilisant plusieurs modèles de régression (linéaire, polynomiale, exponentielle et multivariée). L’objectif est de comprendre les différences entre ces modèles et de démontrer le processus complet de prétraitement des données, analyse de corrélations, modélisation et évaluation de performance.
--Données utilisées :
.PIB de la France depuis la Banque mondiale
.Population et inflation
.Croissance annuelle du PIB

--Étapes principales :
1/Extraction et nettoyage des données : suppression des valeurs manquantes, fusion des datasets, création de nouvelles features (ex. PIB_lag1).
2/Analyse exploratoire : étude des corrélations, visualisation des relations entre variables (scatter plots, heatmaps).
3/Modélisation :
.Régression linéaire simple
.Régression polynomiale (degré 2)
.Régression exponentielle
.Régression linéaire multiple avec nouvelles features
4/Évaluation des modèles : calcul des métriques R² et RMSE, comparaison des performances, visualisation des résultats.
--Résultats clés :
.Les modèles simples (linéaire, polynomiale, exponentielle) montrent les limites de la régression sur des données fortement croissantes.
.La régression linéaire multiple avec les nouvelles features (population, inflation, croissance annuelle, PIB_lag1) fournit le meilleur modèle selon le R² et le RMSE.
--Objectif pédagogique :
.Comprendre et comparer différents types de modèles de régression.
.Savoir prétraiter et enrichir un dataset réel avant modélisation.
.Évaluer et interpréter la performance des modèles de manière pratique.
