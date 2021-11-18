Exercice 2
==========

Le but de cet exercice est de créer une fonction réalisant un clustering spectral.

1. Créer deux datasets en utilisant les fonctions make_circles et make_moons
2. Appliquer l'algorithme KMeans et visualiser les clusters pour les deux datasets
3. Le but de cette question est de créer une fonction spectral_clustering qui, pour un nuage de points et un nombre de clusters k, renvoie une liste de labels
3. 1. Calculer l'ensemble des distances pour chaque paire de points dans une matrice carrée (n, n)
3. 2. Transformer cette matrice en matrice de similarité via un kernel gaussien exp(-d**2)
3. 4. Construire un graphe à partir de cette matrice et en déduire la matrice laplacienne
3. 5. Construire un embedding spectral
3. 6. Appliquer KMeans sur l'embedding spectral
4. Visualiser le résultat du clustering spectral sur les deux datasets