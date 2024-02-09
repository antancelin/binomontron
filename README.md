# Binomontron


## Réalisation d'une application, en Python, qui permet de générer des binômes, à partir d'une base de données contenant la liste d'élèves d'une promotion.

Cette application se décompose en 2 parties :

• Une base de données (en MySQL) : pour commencer, cette base contient une simple table qui liste les élèves de la promotion.

• Le code de l'application (en Python) : dans un premier temps, le code créé des binômes au hasard. Il faut faire attention à ce que l’élève n'appartienne qu'à une seule et unique équipe et que tous les élèves aient un binôme. Les listes des binômes, ainsi que leur constitution, sont à afficher.

Tous les échanges avec l'utilisateur (affichages et saisies) se font sur la console.

​
### Évolutions possibles :

• Permettre de créer des groupes de 3, 4 ou plus.
• Structurer le code sous forme de fonctions.
• Afficher l’adresse mail d’un élève demandé.
• Stocker en base les groupes constitués, avec leurs dates de création.
• Revoir l’algorithme pour que le tirage au sort assure que les groupes soient différents du tirage précédent.
