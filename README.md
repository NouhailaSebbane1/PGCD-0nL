# PGCD-0nL
Le PGCD (Plus Grand Commun Diviseur) de deux nombres est le plus grand nombre entier qui divise les deux nombres sans reste. Voici un programme qui est codé avec C qui nous permet de calculer le PGCD♡
            
     #include <stdio.h>
            
     int main() {
      int N, L, X;
    // Étape1: Lecture des deux nombres
    printf("Entrez deux nombres entiers : ");
    scanf("%d %d", &N, &L);

    // Étape2:on utilise la boucle  Tant que  pour vérifier que L n'est pas nul

    while (L != 0) {
        X = L;      // Étape 3: Gardons la valeur de L

        L = N % L;     // Étape 4:L devient le reste de N divisé par L
        N = X;      // Étape5 N prend l’ancienne valeur de L
    }

    //Étape 6:  Affichage du résultat

    printf("Le PGCD est : %d\n", N);

    return 0;ᯓ˖ᡣ𐭩
    }
