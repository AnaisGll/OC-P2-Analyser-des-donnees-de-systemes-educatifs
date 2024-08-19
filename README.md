# OC-P2 : Analyser-des-donnees-de-systemes-educatifs

Pour ce projet, je suis data Scientist pour une startup de la EdTech, nommé **Academy**. C’est une start-up qui propose du contenu de formation en ligne niveau lycée et supérieur. 

Academy souhaite étendre ses services à l'international. Mon rôle consiste à réaliser une analyse pré-exploratoire des données éducatives fournies par la Banque Mondiale des données. 

Cette analyse vise ainsi à identifier les pays avec un fort potentiel de client pour les services d’Academy ainsi que l’évolution de ce potentiel.

# Missions

- Valider la qualité de ce jeu de données (comporte-t-il beaucoup de données manquantes, dupliquées ?)
- Décrire les informations contenues dans le jeu de données (nombre de colonnes ? nombre de lignes ?)
- Sélectionner les informations qui semblent pertinentes pour répondre à la problématique (quelles sont les colonnes contenant des informations qui peuvent être utiles pour répondre à la problématique de l’entreprise ?)
- Déterminer des ordres de grandeurs des indicateurs statistiques classiques pour les différentes zones géographiques et pays du monde (moyenne/médiane/écart-type par pays et par continent ou bloc géographique)
 
Ce travail permettra de déterminer si ce jeu de données peut informer les décisions d'ouverture vers de nouveaux pays. 

# Le jeu de données 

Le jeu de données se compose de 5 fichiers csv :

- **EdStatsCountry** est un fichier qui liste des pays avec diverses informations à leurs sujets (géographique, économiques, etc…). Il se compose de 241 lignes et 32 colonnes.

- **EdStatsCountry-Serie** apporte des commentaires divers par pays et par indicateurs. Il se compose de 613 lignes et 4 colonnes. 
 
- **EdStatsData** contient les valeurs mesurées par pays, par indicateur et par année entre 1970 et 2100. Il se compose de 886930 lignes et 70 colonnes.

- **EdStatsFootNote** contient des informations sur des indicateurs en commun avec EdStatsData. Il se compose de 643638 lignes et 5 colonnes.

- **EdStatsSeries** contient les définitions des indicateurs ainsi qu’une classification des ces indicateurs par topic. Il contient 3665 lignes et 21 colonnes.


# Compétences évaluées

- Mettre en place un environnement Python
- Utiliser un notebook Jupyter pour faciliter la rédaction du code et la collaboration
- Effectuer une analyse univariée et des représentations graphiques avec une librairie
- Maîtriser les opérations fondamentales du langage Python pour la Data Science
- Manipuler des données avec des librairies Python spécialisées

# Livrables

- Un Jupyter Notebook comportant les analyses pré-exploratoires réalisées.
- Un support de présentation pour la soutenance.
