# house-price-prediction
 House Price Prediction

Ce projet permet de prédire le prix des maisons en utilisant un modèle de Régression Linéaire basé sur des caractéristiques immobilières (surface, nombre de chambres, climatisation, etc.).
 Fonctionnalités

    Nettoyage automatique : Gestion des valeurs manquantes et conversion des types de données.

    Encodage : Transformation des variables textuelles (yes/no) en valeurs numériques via One-Hot Encoding.

    Modélisation : Utilisation de scikit-learn pour entraîner une régression linéaire.

    Visualisation : Génération d'un graphique comparant les prix réels aux prix prédits par le modèle.

Prérequis

Pour faire fonctionner ce code, tu dois avoir installé les bibliothèques suivantes :
Bash

pip install pandas matplotlib scikit-learn

 Structure du projet

    House_Price_Prediction.py : Le script principal contenant tout le pipeline de traitement.

    Housing.csv : Le dataset contenant les données immobilières (formaté avec des ;).

 Comment utiliser

    Assure-toi que le fichier Housing.csv est bien dans le même dossier que le script.

    Lance le script via ton terminal VS Code :
    Bash

    python House_Price_Prediction.py

 Interprétation des résultats

    MSE (Mean Squared Error) : Mesure l'erreur moyenne entre la prédiction et la réalité (plus elle est basse, meilleur est le modèle).

    R² score : Indique la qualité de la prédiction (un score proche de 1 signifie que le modèle explique très bien les variations de prix).
