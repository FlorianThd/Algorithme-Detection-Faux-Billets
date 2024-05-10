# Création d'un algorithme de détection de faux billets 💸

🇬🇧 See below for the English version 🇬🇧

👨‍🎓 Projet de fin d'études réalisé en juin 2023 dans le cadre de la formation diplômante "Data Analyst" d'OpenClassRooms.
<br>🛠 Mots clés : **Machine Learning, prédictions, K-means, régression logistique, régression linéaire.**

<br>

Le projet en quelques mots :

Notre mission était ici de concevoir un algorithme de détection de faux billets pour une institution publique fictive garante de l'intégrité de la monnaie en circulation. À partir de six caractéristiques d'un billet de banque (hauteur, largeur, longueur de la diagonale, etc), l'algorithme devait pouvoir déterminer si celui-ci était vrai ou faux.

Pour pouvoir construire et entraîner notre algorithme, nous avions à notre disposition les caractéristiques de 1500 billets, 500 faux et 1000 vrais.

La stratégie mise en place a été de comparer deux méthodes de prédictions, pour ensuite choisir celle qui donnerait les meilleurs résultats (celle qui donnerait le moins de faux positifs et de faux négatifs).

Les méthodes utilisées sont les suivantes :

- Un algorithme de classification non-supervisée : la méthode K-means
- Un algorithme de classification supervisée : une régression logistique

Après avoir testé nos modèles sur notre échantillon de 1500 billets, nous constations que la méthode K-means permettait une prédiction correcte (un billet prédit comme étant vrai est-il réellement vrai ? Un billet prédit faux réellement faux ?) dans 98.53 % des cas, tandis que la régression logistique permettait une prédiction correcte dans 99.2 %, et fut donc retenu pour notre client.

<br/>

➡️ Rendez-vous ici pour découvrir le [notebook du projet](https://github.com/FlorianThd/Algorithme-Detection-Faux-Billets-en-Python) <br>
✏️ N'hésitez pas à me contacter si vous avez des remarques ou questions via [mon Linkedin](https://www.linkedin.com/in/florian-thouraud)


<br/><br/>


## 🇬🇧 English version 🇬🇧

<br />
👨‍🎓 This was part of an end-of-studies project carried out in June 2023 as part of the OpenClassRooms "Data Analyst" diploma course.
<br> 🛠 Key-words : **Machine Learning, prédictions, K-means, régression logistique, régression linéaire.**

<br>
<br>
<br>

The project in a nutshell:

Our mission here was to design a counterfeit banknote detection algorithm for a fictitious public institution guaranteeing the integrity of the currency in circulation. Based on six characteristics of a banknote (height, width, diagonal length, etc.), the algorithm had to be able to determine whether it was genuine or counterfeit.

To build and train our algorithm, we had at our disposal the characteristics of 1,500 banknotes, 500 counterfeit and 1,000 genuine.

The strategy we adopted was to compare two prediction methods and then choose the one that would give the best results (the one with the fewest false positives and false negatives).

The methods used were as follows:

 - An unsupervised classification algorithm: the K-means method
 - A supervised classification algorithm: logistic regression

After testing our models on our sample of 1,500 notes, we found that the K-means method provided a correct prediction (is a note predicted to be true really true? Is a note predicted to be false really false?) in 98.53% of cases, while logistic regression provided a correct prediction in 99.2% of cases, and was therefore selected for our client.
<br></br>
<br>
➡️ Access to the notebook of the project [here](https://github.com/FlorianThd/Algorithme-Detection-Faux-Billets-en-Python).<br>
✏️ Please do not hesitate to contact me if you have any comments or questions via [my Linkedin](https://www.linkedin.com/in/florian-thouraud)
