# OC-P1 : Analyser-des-donnees-de-systemes-educatifs
Analysez des données de systèmes éducatifs

Pour ce projet, je suis data Scientist pour une startup de la EdTech, nommé **Academy**. C’est une start-up qui propose du contenu de formation en ligne niveau lycée et supérieur. 

Academy souhaite étendre ses services à l'international. Mon rôle consiste à réaliser une analyse pré-exploratoire des données éducatives fournies par la Banque Mondiale des données. 

Cette analyse a pour but :
- Premièrement de décrire les informations contenues dans ce jeu de donnée et d’en valider la qualité 
- Puis de sélectionner les informations qui semblent pertinentes pour répondre à la problématique de l’expansion à l’international

Cette analyse vise ainsi à identifier les pays avec un fort potentiel de client pour les services d’Academy ainsi que l’évolution de ce potentiel. Ce travail permettra de déterminer si ce jeu de données peut informer les décisions d’ouverture vers de nouveaux pays.

Le jeu de données se compose de 5 fichiers csv :
- **EdStatsCountry** est un fichier qui liste des pays avec diverses informations à leurs sujets (géographique, économiques, etc…). Il se compose de 241 lignes et 32 colonnes.

- **EdStatsCountry-Serie** apporte des commentaires divers par pays et par indicateurs. Il se compose de 613 lignes et 4 colonnes. 
 
- **EdStatsData** contient les valeurs mesurées par pays, par indicateur et par année entre 1970 et 2100. Il se compose de 886930 lignes et 70 colonnes.

- **EdStatsFootNote** contient des informations sur des indicateurs en commun avec EdStatsData. Il se compose de 643638 lignes et 5 colonnes.

- **EdStatsSeries** contient les définitions des indicateurs ainsi qu’une classification des ces indicateurs par topic. Il contient 3665 lignes et 21 colonnes.
