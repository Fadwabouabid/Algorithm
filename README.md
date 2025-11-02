# Algorithm
Début
    Écrire "Entrer une phrase terminée par un point : "
    Lire phrase

    longueur ← 0
    nb_mots ← 1        // on suppose qu’il y a au moins un mot avant le point
    nb_voyelles ← 0
    voyelles ← "aeiouAEIOU"

    Pour chaque caractère c dans phrase faire
        longueur ← longueur + 1

        Si c = ' ' alors
            nb_mots ← nb_mots + 1
        FinSi

        Si c est dans voyelles alors
            nb_voyelles ← nb_voyelles + 1
        FinSi
    FinPour

    Écrire "Longueur de la phrase : ", longueur
    Écrire "Nombre de mots : ", nb_mots
    Écrire "Nombre de voyelles : ", nb_voyelles
Fin
