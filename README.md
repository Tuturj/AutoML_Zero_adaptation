# AutoML_Zero_adaptation
## À propos d’AutoML-Zero

Ce projet repose sur **AutoML-Zero**, une approche de recherche évolutive développée par Google pour **découvrir automatiquement des algorithmes de machine learning à partir de zéro**.  
Grâce à une population de petits programmes soumis à des opérations de mutation et de sélection au fil des générations, AutoML-Zero est capable de réinventer des techniques fondamentales (réseaux de neurones, rétropropagation, régression linéaire…) et de générer des modèles compétitifs sur des tâches de classification d’images, sans intervention humaine directe.  

Dans ce dépôt, j’ai étendu AutoML-Zero pour :
- Adapter les tâches existantes pour l'utilisationde données en formats plus lisible (.csv) que l'implémentation original (.bin).
- Générer des datasets à partir de série temporelle
  
## Objectif et intuition

L'objectif principal de cette extension est la prédiciton de volatilité future à court terme, on espère, en gardant AutoML-Zero comme base, découvrir et redécouvrir des algorithme. 

Vous trouverez dans les sections suivantes :
1. **Installation** – instructions pour configurer l’environnement.  
2. **Utilisation** – commandes pour lancer les expériences AutoML.  
3. **Résultats** – synthèse des algorithmes découverts et performances obtenues.  
