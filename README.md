# Analyse de Sentiments sur des Tweets

Ce projet applique des techniques de prétraitement de texte et d'apprentissage automatique pour prédire le sentiment de tweets.

## Contenu du projet
- **notebook.ipynb** : Notebook principal, entièrement documenté en français, présentant toutes les étapes du projet (prétraitement, entraînement, évaluation, comparaison des modèles).
- **requirements.txt** : Liste des bibliothèques Python nécessaires.
- **train.csv / test.csv** : Jeux de données utilisés pour l'entraînement et le test.

## Démarche suivie
1. **Prétraitement** : Nettoyage, normalisation, suppression des stopwords, tokenisation.
2. **Vectorisation** : Transformation des textes en vecteurs numériques (TF-IDF).
3. **Modélisation** : Entraînement de plusieurs modèles (Naive Bayes, Régression Logistique, Arbre de Décision, Forêt Aléatoire).
4. **Évaluation** : Comparaison des scores de précision, affichage des matrices de confusion et des rapports de classification.
5. **Prédiction manuelle** : Fonction pour tester la prédiction de sentiment sur un texte donné.

## Lancer le projet
1. Installer les dépendances :
   ```bash
   pip install -r requirements.txt
   ```
2. Ouvrir le notebook `notebook.ipynb` dans Jupyter ou VS Code et exécuter les cellules.

## Résultats
- La régression logistique et la forêt aléatoire offrent les meilleures performances.
- Le prétraitement du texte améliore significativement la qualité des prédictions.

## Auteur
Projet réalisé dans le cadre du cours de Data Science à l'INSEA.
