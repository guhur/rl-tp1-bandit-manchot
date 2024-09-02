# Introduction à l'apprentissage par renforcement - TP 1 : Les manchots multi-bras

Ce dépôt contient le code source et les résultats associés au premier travail pratique (TP1) du cours "Introduction à l'apprentissage par renforcement". Le sujet de ce TP est axé sur les bandits manchots multi-bras, un problème classique en apprentissage par renforcement.

### Structure du dépôt

- **`tp1.ipynb`**: Notebook Jupyter contenant tout le code et les analyses pour ce TP. Ce fichier doit être complété et commenté en fonction des questions posées dans l'énoncé.
- **`groupe.txt`**: Fichier texte contenant les informations des membres du groupe (Noms, Prénoms, Emails, Numéros d'étudiant) conformément au format demandé.
- **`export/`**: Ce répertoire contient les différentes versions exportées du notebook :
  - `tp1.pdf`: Version PDF du notebook.
  - `tp1.html`: Version HTML du notebook.
- **`figures/`**: Répertoire destiné à contenir les figures et graphiques générés au cours de l'exécution du notebook.

### Instructions

#### 1. Installation des dépendances

Les dépendances nécessaires pour exécuter le notebook sont listées dans la première cellule de code. Vous pouvez les installer en exécutant la cellule ou en exécutant la commande suivante dans votre terminal :

```bash
pip install matplotlib tqdm numpy ipympl opencv-python
```

#### 2. Exécution du notebook

Le notebook `tp1.ipynb` est structuré de manière séquentielle avec des questions théoriques et pratiques à traiter. Il est recommandé de suivre l'ordre des cellules et de ne pas en modifier l'organisation. Veillez à ce que les graphes et les résultats soient bien présents et interprétés dans vos réponses.

#### 3. Commentaires et mise en forme

1/4 de la note finale est liée à la mise en forme du notebook. Pensez à :
- Nettoyer les outputs inutiles (messages d'installation, débogage, etc.).
- Soigner la présentation des figures (axes, échelles, légendes, etc.).
- Commenter vos résultats en les reliant aux concepts théoriques vus en cours.

#### 4. Rendu du TP

Le TP doit être rendu sous forme d'une archive ZIP contenant :
- Le notebook `tp1.ipynb` complété.
- Les versions PDF et HTML du notebook.
- Le fichier `groupe.txt` avec les informations des membres du groupe.

### Questions abordées

Le TP couvre les thématiques suivantes :
- **Bandits manchots** : Implémentation de plusieurs stratégies pour résoudre le problème des bandits manchots (algorithme glouton, Upper Confidence Bound, échantillonnage de Thompson).
- **Analyse de regret** : Calcul et analyse du regret pour les différentes stratégies.
- **Visualisation et comparaison** : Création de figures pour illustrer les résultats obtenus.

Chaque question dans le notebook est suivie d'une cellule de code pour l'implémentation et d'une cellule markdown pour ajouter des commentaires et analyses.

### Conclusion

La dernière section du notebook vous demande de comparer les performances des différents algorithmes (glouton, UCB, Thompson) dans un scénario où un grand nombre de vaccins est disponible, et de faire le lien avec la "malédiction de la dimension".

### Auteurs

Chaque membre du groupe doit être listé dans le fichier `groupe.txt` avec les informations suivantes :
- Nom
- Prénom
- Email
- Numéro d'étudiant

### Remarques finales

Assurez-vous que toutes les cellules du notebook ont bien été exécutées avant de soumettre le TP. Les résultats et les graphiques doivent être clairement présentés, et les commentaires doivent refléter une compréhension des concepts théoriques.

Bon travail !
