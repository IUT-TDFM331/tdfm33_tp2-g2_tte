Les tests mettent autant de temps car :
isWellSortedLargeArrays prend 22314 ms a se faire car elle range un array de tres grande taille (50000 ici)

#2)
Les tests ne fonctionnent plus et nous avons l'erreur : "java : class, interface, or enum expected"

#4)
Nous remarquons que la methode reverseSort() est en rouge car elle est à l'exterieur des balises de fermeture de la classe.
Nous récupérons les erreurs sans pouvoir savoir au préalable qu'il y avait des erreurs au sein du projet.

#6)
Nous remarquons que que nous avons un nouveau répertoire à la racine de notre projet nommé '.github/workflows'.

#7)
Nous avons déplacé la methode mergeSort à l'interieur de la classe 'SortAlgorithms.java'.

#9)
Les tests passent sauf le test qui doit fail.

#10)
La validation n'a pas identifié l'erreur dans les tests. C'est normal car dans le processus de compilation du logiciel, on n'exécute pas les tests.