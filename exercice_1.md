Exercice 1
==========

Dans cet exercice, on réaliser faire la bipartition d'un graphe en utilisant le vecteur de Fielder (le deuxième plus petit vecteur propre)

1. Chercher dans la documentation networkx et créer un barbell graph composé de deux graphes complets de 20 noeuds liés à une chaîne de 6 noeuds
2. Chercher dans la documentation networkx et construire la matrice laplacienne
3. Quelle est la valeur du produit matriciel entre L et le vecteur 1 ?
3. Utiliser la fonction eigsh de scipy pour décomposer L en 2 vecteurs propres, dans l'ordre croissant des valeurs propres
4. Utiliser le vecteur de Fiedler (le deuxième vecteur propre) pour visualiser la bipartition du barbell graph