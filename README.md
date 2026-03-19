1. #include <stdio.h>

int main()
{
    float velocidade, tempo, distancia;
    
    scanf("%f", &velocidade);
    scanf("%f", &tempo);
    
    distancia = (velocidade * tempo);
    
    printf("A distancia percorrida sera: %.2f\n", distancia);

    return 0;
}

2. #include <stdio.h>

int main()
{
   float x, resultado;
   
   scanf("%f", &x);
   
   resultado = (x + 4) * (x - 6);
   
   printf("O resultado sera: %.2f\n", resultado);
   
   
    return 0;
    
}
3.#include <stdio.h>
#include <math.h>

int main()
{
    float co, ca, h;
    scanf("%f", &co);
    scanf("%f", &ca);
    
    h = sqrt ( pow(co,2) + pow(ca,2));
    
    printf("a hipotenusa sera: %.2f", h);
    

    return 0;
}
