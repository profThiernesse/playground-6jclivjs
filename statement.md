# Rappel

## Exemple exécutable

```C runnable
#include <stdio.h>

int main() {
    int a;
    int *pta;
    
    a=8;
    pta = &a;
    
    //Affichage de la valeur de a grâce à a
    printf("Valeur de a : %d\n",a);    
    //Affichage de la valeur de a grâce à pta
    printf("Valeur de a : %d\n",&pta);
    
    //Affichage de l'adresse de a grâce à a
    printf("Adresse de a : %p\n",&a);
    //Affichage de l'adresse de a grâce à pta
    printf("Adresse de a : %p\n",pta);
    
    return 0;
}

```

# Quizz

Afin de tester la compréhension la matière, complèter [ce questionnaire](https://goo.gl/forms/C3WkjJmB18vOww2C3)
