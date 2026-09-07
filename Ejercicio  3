#include <stdio.h>

int main() {
    int vector[5];
    int posicion;
    char continuar;

    // Carga del vector
    for(int i = 0; i < 5; i++) {
        printf("Ingrese el dato %d: ", i + 1);
        scanf("%d", &vector[i]);
    }

    // Consulta de posiciones
    do {
        printf("\nQue posicion desea consultar (0 a 4)? ");
        scanf("%d", &posicion);

        if(posicion >= 0 && posicion < 5) {
            printf("El valor en la posicion %d es: %d\n",
                   posicion, vector[posicion]);
        } else {
            printf("Posicion invalida.\n");
        }

        printf("Desea consultar otra posicion? (s/n): ");
        scanf(" %c", &continuar);

    } while(continuar == 's' || continuar == 'S');

    printf("Programa finalizado.\n");

    return 0;
}
