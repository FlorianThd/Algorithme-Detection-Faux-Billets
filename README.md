# Algorithme-DetectionFauxBillets

Projet fictif de fin d'études réalisé en juin 2023 dans le cadre de la formation diplomante "Data Analyst".
Mots clés : Machine Learning, prédictions, K-means, Régression logistique, régression linéaire.

Le projet en quelques mots :
Notre mission était ici de concevoir en moins d'un mois un algorithme de détection de faux billets.
L'utilisateur final devait pouvoir renseigner les caractéristiques d'un billet de banque, et l'algoritme devait être capable de déterminer si celui-ci était vrai, ou faux.

Les données à notre disposition étaient six caractéristiques (hauteur, largeur, diagonale, etc) de 1500 billets, 500 faux et 1000 vrais.

La stratégie mise en place a été de comparer deux méthodes de prédictions pour conserver la plus performante:
- Un algorithme de classification non-supervisée : la méthode K-means
- Un algoritme de classification supervisée : une régression logistique

Après avoir testé notre modèle sur notre échantillon des 1500 billets, nous constations que la méthode K-means permettait une prédiction correcte dans 98.53 % des cas, tandis que la régression logistique permettait une prédiction correcte dans 99.2 %, et fut donc retenu pour notre client. 


N'hésitez pas si vous souhaitez plus de précisions !

