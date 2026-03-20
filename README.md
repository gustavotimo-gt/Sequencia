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

4. #include <stdio.h>

int main() { float v1, v2, v3, media;

scanf("%f", &v1); scanf("%f", &v2); scanf("%f", &v3);

media = ((v1 * 2 ) + (v2 * 5) + (v3 * 7)) / (2 + 5 + 7) ;


printf(" A media e: %.2f\n", media);
return 0; }

5. #include <stdio.h>
#include <math.h>

int main()
{
    float a, b, c, delta, x1, x2;
    
    scanf("%f", &a);
    scanf("%f", &b);
    scanf("%f", &c);
    
    delta = pow(b, 2) - (4 * a * c);
    
    x1 = (-b + sqrt(delta)) / (2 * a);
    
 x2 = (-b - sqrt(delta)) / (2 * a);
    printf("delta sera: %.2f\n", delta);
    printf("a solucao x1 sera: %.2f\n", x1);
    printf("a solucao x2 sera: %.2f\n", x2);

    6. #include <stdio.h>

int main()
{
   float v, v0, a, t ;
   
   scanf("%f", &v0);
   scanf("%f", &a);
   scanf("%f", &t);
   
   v = v0 + (a * t);
   
   printf("a velocidade final sera: %.2f\n", v);
   
   
    return 0;
}


    
    
    return 0;
}

