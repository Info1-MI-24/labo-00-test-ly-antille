# Premier laboratoire de programmation

Ceci est un fichier README.md.

Un fichier README est un fichier qui contient des informations sur d'autres fichiers dans un répertoire. Il est généralement affiché sur la page principale du répertoire.

> Expliquez ce que fait votre programme et comment il fonctionne.

## Réponse et modifications apportées

Ce programme permet de faire une addition entre deux nombres entiers et il affiche le résultat final. Il utilise la bibliothèque stdio.h pour permettre l'utilisation de la fonction printf() (qui sert à afficher du texte). Dans la fonction main() {}, trois variables de type entier sont définies (val_1 avec une valeur de 12, val_2 avec une valeur de 34, et sum qui stocke la somme des deux premières variables, ce qui fait 46 comme résultat). La fonction printf() est ensuite utilisée pour afficher le message suivant dans le terminal : "La somme de 12 et 34 fait : 46", en insérant les valeurs des variables dans les espaces réservés %d, avec d qui correspond au fait que les nombres sont des entiers. Enfin, le programme se termine avec return 0; ce qui signifie que tout s'est bien déroulé comme prévu.

J'ai renommé les variables utilisées dans le programme (val1 -> val_1, ...) et j'ai remplacé les "..." dans l'affichage par le mot "somme", qui correspond au résultat renvoyé par le programme. J'ai également rajouté un "\n" pour revenir à la ligne dans le terminal après l'affichage du message "La somme de 12 et 34 fait : 46".