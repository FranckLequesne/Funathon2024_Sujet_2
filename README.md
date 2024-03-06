# Funathon 2024 - Sujet 2 :star:

Réaliser un tableau de bord mensuel du trafic aérien en se servant directement sur data.gouv.fr

## Grandes parties

1. Importer les données mensuelle de trafic sur [data.gouv.fr](https://www.data.gouv.fr/fr/datasets/trafic-aerien-commercial-mensuel-francais-par-paire-daeroports-par-sens-depuis-1990/)

2. Faire la partie UI/FrontEnd du serveur Shiny
   - Créer une interface avec un panneau latéral et un panneau principal
   - Mettre des inputs (listes de sélection, bouton radio, etc.) dans le panneau latéral 
   - Utiliser les _dataTableOutput_ du package _DT_ pour afficher les données en tableau dynamique dans le panneau principal

3. Faire la partie Serveur/BackEnd du serveur Shiny
   - Relier les inputs et les outputs

## Remarques

Exemple préparé et accessible sur https://github.com/PierreG34/RTraffic
