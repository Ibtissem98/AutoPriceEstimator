Description

Ce projet consiste à prédire les prix des voitures à partir de différentes caractéristiques 
comme l'année, le kilométrage, la consommation de carburant, etc. L'objectif est 
d'explorer différentes techniques de régression, y compris la régression linéaire, Ridge 
et la transformation polynomiale, pour améliorer les performances du modèle. Le 
projet utilise des méthodes d'évaluation telles que l'erreur quadratique moyenne (MSE) 
et le coefficient de détermination (R²) pour mesurer l'efficacité du modèle.

Méthodologie

1. Préparation des données : Les données ont été nettoyées et préparées en 
traitant les valeurs manquantes et les duplicatas.
2. Analyse exploratoire : Une analyse des corrélations entre les variables a été 
effectuée pour identifier les caractéristiques les plus pertinentes pour la 
prédiction du prix.
3. Modélisation :
a. Régression linéaire simple et multiple.
b. Régression Ridge avec régularisation pour éviter le sur-apprentissage.
c. Transformation polynomiale pour ajouter des interactions non linéaires 
entre les variables.
4. Évaluation du modèle : L'évaluation a été réalisée en utilisant une validation 
croisée et des métriques telles que MSE et R². Un processus de recherche par 
grille a été utilisé pour optimiser les paramètres du modèle, en particulier le 
paramètre de régularisation alpha de la régression Ridge.
5. Résultats : Le meilleur modèle a été obtenu avec un alpha de 0.01, offrant un R² 
de 0.38, ce qui montre que le modèle explique une partie significative de la 
variabilité des prix des voitures.

Conclusion

Le modèle de régression Ridge avec régularisation a montré des résultats prometteurs, 
bien que des améliorations puissent encore être apportées, notamment en ajoutant 
davantage de caractéristiques ou en optimisant les techniques de modélisation.
Technologies utilisées
• Python
• pandas
• scikit-learn
• seaborn
• matplotlib
