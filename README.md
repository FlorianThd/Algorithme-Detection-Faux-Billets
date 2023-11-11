# Création d'un algorithme de détection de faux billets 💸

👨‍🎓 Projet de fin d'études réalisé en juin 2023 dans le cadre de la formation diplômante "Data Analyst".
<br />🛠 Mots clés : **Machine Learning, prédictions, K-means, régression logistique, régression linéaire.**

---

Le projet en quelques mots :

Notre mission était ici de concevoir un algorithme de détection de faux billets pour une institution publique fictive garante de l'intégrité de la monnaie en circulation. À partir de six caractéristiques d'un billet de banque (hauteur, largeur, longueur de la diagonale, etc), l'algorithme devait pouvoir déterminer si celui-ci était vrai ou faux.

Pour pouvoir construire et entraîner notre algorithme, nous avions à notre disposition les caractéristiques de 1500 billets, 500 faux et 1000 vrais.

La stratégie mise en place a été de comparer deux méthodes de prédictions, pour ensuite choisir celle qui donnerait les meilleurs résultats (celle qui donnerait le moins de faux positifs et de faux négatifs).

Les méthodes utilisées sont les suivantes :

- Un algorithme de classification non-supervisée : la méthode K-means
- Un algorithme de classification supervisée : une régression logistique

Après avoir testé nos modèles sur notre échantillon de 1500 billets, nous constations que la méthode K-means permettait une prédiction correcte (un billet prédit comme étant vrai est-il réellement vrai ? Un billet prédit faux réellement faux ?) dans 98.53 % des cas, tandis que la régression logistique permettait une prédiction correcte dans 99.2 %, et fut donc retenu pour notre client.

---

👋 Merci de votre lecture !<br>
✏️ N'hésitez pas à me contacter si vous avez des remarques ou questions à FlorianData@pm.me

