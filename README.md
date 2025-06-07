# Valeurs Extrêmes

Analyse des Valeurs Extrêmes – Executive Master Statistique & IA, Paris Dauphine PSL
Ce projet s'inscrit dans le cadre du cours de théorie des valeurs extrêmes du Master Statistique & Intelligence Artificielle à l'université Paris Dauphine PSL. L’objectif est d’explorer la modélisation des événements rares à partir de données réelles via la théorie des valeurs extrêmes (EVT), en mettant l’accent sur deux familles de modèles : la loi des valeurs extrêmes généralisée (GEV) et la distribution des excès généralisés (GPD).

Après avoir sélectionné un jeu de données thématique (ici : indices boursiers du Dow Jones), l’analyse débute par une étude descriptive et la stationnarisation des séries temporelles, nécessaire à l’application de l’EVT. Deux méthodes d’estimation des paramètres sont comparées : le Maximum de Vraisemblance (MLE) et la méthode des moments pondérés (PWM), chacune évaluée à travers l’ajustement des modèles et l’incertitude des prédictions.

Les étapes clés incluent :

Analyse exploratoire et statistique descriptive
Choix d’un seuil pertinent ou découpage en blocs
Ajustement des modèles GEV et/ou GPD
Visualisation des niveaux de retour (return levels)
Estimation de la valeur de retour pour des horizons de 10, 100 et 1000 ans
Calcul d’intervalles de confiance à 95% pour chaque paramètre et niveau de retour
Interprétation des résultats en lien avec la problématique étudiée
Ce projet met en pratique des outils R spécialisés (evd, evir, ismev, fExtremes, extRemes) et vise à illustrer la robustesse de la théorie des valeurs extrêmes pour modéliser des risques rares dans des domaines variés (finance, environnement…).
