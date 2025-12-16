#######################################################################
#  Binome : ALINOT Killian / SIRI Baptiste
# #######################################################################

## Jeu de données : pré-traitement

Donnez la liste des features et ce qu'elles représentent (préciser les éventuels changements effectués en pré-traitement ou si pas de changement)

## Expérimentation 1 : Comparaison de modèles par défaut

* Jeux de données utilisé : 
  * Taille ensemble d'entrainement (nb lignes et nb colonnes) : 133052 lignes et 9 colonnes
  * Taille ensemble de test (nb lignes et nb colonnes) : 33263 lignes et 9 colonnes

* Résultats (hyper-paramètres par défaut)

|  Evaluation en train | Random Forest |   XGBoost   |   Adaboost  |
|----------------------|---------------|-------------|-------------|
|  Accuracy            |     91.71%    |    79.96%   |    79.22%   |
|----------------------|---------------|-------------|-------------|
|  Temps calcul        |     13.97s    |    7.35s    |    3.24s    |
|----------------------|---------------|-------------|-------------|
|  Matrice confusion   |   72713  5805 | 65305 13213 | 65587 12931 |
|                      |   5226  49308 | 13457 41077 | 14713 39821 |
|----------------------|---------------|-------------|-------------|

|  Evaluation en test  | Random Forest |   XGBoost  |  Adaboost  |
|----------------------|---------------|------------|------------|
|  Accuracy            |     77.71%    |   79.71%   |   79.23%   |
|----------------------|---------------|------------|------------|
|  Matrice confusion   |   16053  3541 | 16280 3314 | 16388 3206 |
|                      |   3874  9795  | 3435 10234 | 3703 9966  |
|----------------------|---------------|------------|------------|

* Commentaires et Analyse : c bizarre !


## Expérimentation 2 : Comparaison Modèles ML par défaut
* Jeux de données utilisé : 
  * Taille ensemble d'entrainement (nb lignes et nb colonnes) : 
  * Taille ensemble de test (nb lignes et nb colonnes) : 

### Random Forest (RF)
* Processus d'entrainement : 
  * Recherche des hyperparamètres
   * Listes des hyperparamètres testés et valeurs : 
  * Nombre de plis pour la validation croisée : 
  * Nombre total d'entrainement : 
* Résultats : 
  * Meilleurs hyperparamètres : 
  * Performances en entraintement : 
   * Accuracy : 
   * Temps de calcul : 
   * Matrice de Confusion : 
  * Performance en test : 
   * Accuracy : 
   * Temps de calcul : 
   * Matrice de Confusion : 
  * Commentaires / analyses (par rapport résultat expe 1)

### ADABOOST 
* Processus d'entrainement : 
  * Recherche des hyperparamètres
   * Listes des hyperparamètres testés et valeurs : 
  * Nombre de plis pour la validation croisée : 
  * Nombre total d'entrainement : 
* Résultats : 
  * Meilleurs hyperparamètres : 
  * Performances en entraintement : 
   * Accuracy : 
   * Temps de calcul : 
   * Matrice de Confusion : 
  * Performance en test : 
   * Accuracy : 
   * Temps de calcul : 
   * Matrice de Confusion : 
  * Commentaires / analyses (par rapport résultat expe 1)


### XGBOOST
* Processus d'entrainement : 
  * Recherche des hyperparamètres
   * Listes des hyperparamètres testés et valeurs : 
  * Nombre de plis pour la validation croisée : 
  * Nombre total d'entrainement : 
* Résultats : 
  * Meilleurs hyperparamètres : 
  * Performances en entraintement : 
   * Accuracy : 
   * Temps de calcul : 
   * Matrice de Confusion : 
  * Performance en test : 
   * Accuracy : 
   * Temps de calcul : 
   * Matrice de Confusion : 
  * Commentaires / analyses (par rapport résultat expe 1)

## Expérimentation 3 : Comparaison des "meilleurs modèles

* Jeux de données utilisé : 
  * Taille ensemble d'entrainement (nb lignes et nb colonnes) : 
  * Taille ensemble de test (nb lignes et nb colonnes) : 

* Résultats des meilleurs modèles obtenus dans Expe 2

|  Evaluation en train | Random Forest | Adaboost | XGBoost |
|----------------------|---------------|----------|---------|
|  accuracy            |               |          |         |
|----------------------|---------------|----------|---------|
|  Temps calcul        |               |          |         |
|----------------------|---------------|----------|---------|
|  Matrice confusion   |               |          |         |
|----------------------|---------------|----------|---------|

|   Evaluation en test | Random Forest | Adaboost | XGBoost |
|----------------------|---------------|----------|---------|
|  accuracy            |               |          |         |
|----------------------|---------------|----------|---------|
|  Temps calcul        |               |          |         |
|----------------------|---------------|----------|---------|
|  Matrice confusion   |               |          |         |
|----------------------|---------------|----------|---------|

* Commentaires et Analyse : 

## Expérimentation 4 : inférence sur un autre jeu de données (optionnel)
Résultats / Commentaires / Analyses : 

## Expérimentation 5 : impact de la taille du jeu de données
Résultats / Commentaires / Analyses : 

## Modèle choisi pour la suite : 
* quel modèle : 
* pourquoi ? 

## Explicabilité : "permutation feature importance"

* Résultats obtenus : 
* Analyses :

## Explicabilité : avec LIME et SHAP

* Méthode LIME
  * Exemple(s) choisi(s)
  * Résultats
  * Commentaires / analyses
* Méthode SHAP
  * Exemple(s) choisi(s)
  * Résultats
  * Commentaires / analyses
* Comparaison LIME et SHAP
* Analyse summary-plot de SHAP

## Explicabilité : contrefactuelle
Résultats / Commentaires / Analyses : 


