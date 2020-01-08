# Projet Give me some credit (01/2020)

## Objectifs

Estimer si un usager va rembouser ou non son prêt à partir d'un dataset fournit par kaggle.
<br><br>

## Méthodologie

1. Un listing de personnes est disponible (plusieurs milliers), et pour chacune d'entre-elles diverses données :
    - l'âge de la personne
    - son montant de dettes
    - si elle a remboursée son prêt sous 30 jour
    - sa rentrée d'argent
    - si elle est considérée comme vieille
    - ...

2. Un traitement est alors effectué sur ces données brutes afin de compléter les informations disponibles, traiter les données extrèmes ou encore harmoniser les données (entièrement numériques ou non).

3. Un modèle d'apprentissage va alors être créé à base d'un réseau de neurones.

4. Une prédiction est effectuée sur un autre ensemble de données dont le prix est inconnu.

5. Nous soumettons alors les prédictions pour évaluation à Kaggle qui nous retourne un score de précision.
<br><br>

## Méthode d'importation du projet et mise en oeuvre

1. Télécharger depuis le dépot github du projet : https://github.com/thiberged/give.git

2. Extraire le fichier .zip dans un dossier vide sur votre espace de travail.

3. Depuis votre compte kaggle, récupérez les fichiers test et train du challenge Kaggle : https://www.kaggle.com/c/GiveMeSomeCredit/data
<br><br>

## Liens vers les notebooks

- Visualisation des diverses features de la base de données
<center>

[01_visualisation_modification.ipynb](file/01_visualisation_modification.ipynb)
</center>

- Apprentissage du modèle à partir des datasest modifiés et création d'une prédiction
<center>

[02_bigml.ipynb](file/02_bigml.ipynb)
</center>

- Analyse de la prédiction grâce à divers outils
<center>

[03_analyse_prediction.ipynb](file/03_analyse_prediction.ipynb)
</center>

- Evaluation de la prédiction trouvée précédement afin de l'optimiser
<center>

[04_evaluation_prediction.ipynb](file/04_evaluation_prediction.ipynb)
</center>

- Prédiction sur un unique input via le modèle précédement entraîné
<center>

[05_test_solo.ipynb](file/05_test_solo.ipynb)
</center>

- Mise en page puis envoie de la prédiction à kaggle
<center>

[06_submit_kaggle.ipynb](file/06_submit_kaggle.ipynb)
</center>
<br><br>

## Score Kaggle

Score = 0.85527
