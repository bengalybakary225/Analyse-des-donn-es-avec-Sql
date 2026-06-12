# Analyse des données avec SQL ✈️

## Contexte
Ce projet analyse la base de données d'une compagnie aérienne afin d'identifier 
des opportunités pour augmenter le taux d'occupation des vols et améliorer la rentabilité.

## Problématique
La compagnie fait face à plusieurs défis :
- Réglementations environnementales plus strictes
- Taxes de vol plus élevées
- Hausse des coûts de main-d'œuvre

L'objectif est d'analyser les données pour maximiser le revenu moyen par siège.

## Base de données
La base `travel.sqlite` contient 8 tables :
- `bookings` — Réservations
- `tickets` — Billets
- `ticket_flights` — Billets par vol
- `boarding_passes` — Cartes d'embarquement
- `flights` — Vols
- `seats` — Sièges
- `aircrafts_data` — Avions
- `airports_data` — Aéroports

## Analyses réalisées
1. Capacité des sièges par avion et par classe
2. Taux moyen d'occupation par avion
3. Revenu moyen par siège par avion
4. Vue complète taux d'occupation + revenu moyen
5. Analyse du trafic par mois
6. Top 10 des routes les plus rentables
7. Comparaison Economy vs Business vs Comfort

## Technologies utilisées
- Python
- SQL / SQLite
- Pandas
- Matplotlib
- Jupyter Notebook

## Résultats clés
- Le **Boeing 777** a le meilleur taux d'occupation (65.90%)
- La route **Moscow → Khabarovsk** est la plus rentable (753M ₽)
- **Août** est le mois le plus chargé (+31% vs juillet)
- Un billet **Business** rapporte en moyenne 5x plus qu'un billet Economy
