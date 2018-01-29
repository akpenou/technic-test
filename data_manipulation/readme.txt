Test technique

Vous trouverez dans ce test technique un dossier data et un dossier srcs.
Vous devez mettre votre code source dans le dossier srcs.
Vous trouverez les datasets dans le dossier data.

L'exercice est de realiser une regression lineaire sur la consommation electrique nationale.
Vous trouverez un trainset qui vous sert de base d'apprentissage puis les fichiers a predire dans data/test.
Dans data/valid vous avez la vraie consommation au jour J. Vous devez minimiser votre MAPE sur votre trainset personnel.

Attention a coder proprement et documenter le tout.

Vous fournirez un fichier de reponse de la forme pour chaque fichier de data/test:
region.code;date;hour;pred
FRANCE;2017-07-14;00:00;4003
FRANCE;2017-07-14;00:15;3991
FRANCE;2017-07-14;00:30;3959
FRANCE;2017-07-14;00:45;3903
