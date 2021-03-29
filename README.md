# Weather AUSTRALIA

Prédire la pluie du lendemain en entraînant des modèles de classification sur la variable cible RainTomorrow.
Contenu

Ce jeu de données contient environ 10 ans d'observations météorologiques quotidiennes provenant de nombreux endroits en Australie.

Nous devons calculer les éléments suivants :

- Le nombre total de jours, 'n_days'.
- Le nombre de jours avec au moins 1mm ou plus de pluie, 'n_atleast_1mm'.
- Le nombre de jours avec moins de 1mm de pluie, 'n_lessthan_1mm'.
- Pourcentage de jours avec 1mm ou plus de pluie, 'rainy_days_percentage'.


## Analyse des variables du Dataset

- Date
La date de l'observation

- Location
Le nom commun de l'emplacement de la station météorologique.

- MinTemp
La température minimale en degrés Celsius

- MaxTemp
La température maximale en degrés Celsius

- Rainfall
La quantité de pluie enregistrée pour la journée, en mm.

- Evaporation
L'évaporation de la casserole de classe A (mm) dans les 24 heures jusqu'à 9 heures du matin.

- Sunshine
Le nombre d'heures d'ensoleillement dans la journée.

- WindGustDir
La direction de la plus forte rafale de vent dans les 24 heures jusqu'à minuit.

- WindGustSpeed
La vitesse (km/h) de la plus forte rafale de vent au cours des 24 heures précédant minuit.

- WindDir9am
Direction du vent à 9h du matin

- WindDir3pm
Direction du vent à 15h

- WindSpeed9am
Vitesse du vent (km/h) moyennée sur 10 minutes avant 9h.

- WindSpeed3pm
Vitesse du vent (km/h) moyenne sur 10 minutes avant 15h00

- Humidity9h
Humidité (pourcentage) à 9h du matin

- Humidity3pm
Humidité (pourcentage) à 15h

- Pression9am
Pression atmosphérique (hpa) ramenée au niveau moyen de la mer à 9h00

- Pressure3pm 
Pression atmosphérique (hpa) ramenée au niveau moyen de la mer à 15h.

- Nuage9am
Fraction du ciel obscurcie par les nuages à 9h du matin. Elle est mesurée en "oktas", qui sont une unité de huitièmes. Elle indique combien de huitièmes du ciel sont obscurcis par les nuages. Une mesure de 0 indique un ciel complètement dégagé tandis qu'une mesure de 8 indique un ciel complètement couvert.

- Nuage3pm
Fraction du ciel obscurcie par les nuages (en "oktas" : huitièmes) à 15 heures. Voir Cload9am pour une description des valeurs.

- Temp9am
Température (degrés C) à 9h du matin

- Temp3pm
Température (degrés C) à 15h

- RainToday
Booléen : 1 si les précipitations (mm) dans les 24 heures jusqu'à 9 heures dépassent 1mm, sinon 0.

- RainTomorrow
La quantité de pluie prévue pour le lendemain, en mm. Utilisée pour créer la variable de réponse RainTomorrow. Une sorte de mesure du "risque".


