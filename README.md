#include <stdio.h>

int main()
{
    #define tam_max 10
    int Vet1[tam_max];
    int Maior;
    int i;
    
    for (i=0; i<tam_max; i++)
        scanf("%d", &Vet1[i]);
    
    Maior = Vet1[0];
    for(i=0; i<tam_max; i++)
        if(Vet1[i] > Maior)
            Maior = Vet1[i];
    printf("O maior elemento Ã© %d\n", Maior);

    return 0;
}
