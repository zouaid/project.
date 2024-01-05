A: Quelles sont les structures de données à utiliser ?
Les matrices B, C et A sont des tableaux bidimensionnels pour stocker les valeurs des matrices , Le tampon T est un tableau unidimensionnel utilisé comme mémoire tampon pour stocker les résultats intermédiaires produits par les threads producteurs, variables de contrôle du tampon ,
B: Comment allez-vous protéger l'accès à ces données?
Pour protéger l'accès aux données partagées entre les threads (matrices, tampon), vous utiliserez des mécanismes de synchronisation, tels que les mutex (verrous) et les variables de condition ,
C: quels sont les risques?
Conditions de concurrence 
Dépassement de tampon (buffer overflow) 
Problèmes de synchronisation
Gestion des erreurs
