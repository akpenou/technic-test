# Scraping test

Ce test consiste à réaliser un scraper en python ou javascript pour récuperer différentes informations.  
Le site à scraper est [fr.aliexpress.com](https://fr.aliexpress.com  "fr.aliexpress.com"), pour environ 200 écouteurs.
Vous devrez récupérer 4 informations: nom du produit, type d'unité, les dimensions et le poids.
Vous rendrez un fichier csv avec comme champs:  

| colonne | contenu |
| ------- | ------- |
| index | un id unique pour chaque article scrapé |
| nom | qui contient le nom du produit |
| unité | contient le type d'unité du produit |
| poids (en kg) | contient le poids du colis en kg, attention ce doit etre un float ou un nan |
| dimension (en cm) | contient la dimension du colis en cm en string avec la forme suivante 'nn.n x nn.n x nn.n' |

Votre code dois etre dans le dossier scrs et vos resultats dans le dossier data
