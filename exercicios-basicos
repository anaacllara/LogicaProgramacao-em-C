#include <stdio.h>
#include <stdlib.h>
#include <math.h>

/*Ler dois valores A e B e imprimí-los trocados*/
int main(){
    int a,b;
    printf("Escreva dois números: ");
    scanf("%d %d",&a,&b);
    printf("a: %d, e b: %d",a,b);
    const int TEMP= a;
    a=b;
    b=TEMP;
    printf("Números após a mudança, a = %d, b= %d", a ,b);
    return 0;}

/* salário fixo, total de vendas no mês (recebe apenas 15%) e salário final*/
int main(){
    float sal_fixo, vendas, sal_final;

    printf("Escreva o seu salario fixo: ");
    scanf("%f",&sal_fixo);
    printf("Escreva o valor total de vendas efetuadas no mes: ");
    scanf("%f",&vendas);
    vendas = vendas * 0.15;
    sal_final = sal_fixo + vendas;
    printf("Esse e o seu salario final: %.2f", sal_final);
    return 0;
}

/* valor depositado, taxa de 0,7% e valor final com rendimento*/
nt main(){
    float val_depositado, rendimento, tx_juros;
    printf("Digite o valor depositado: ");
    scanf("%f",&val_depositado);

    tx_juros = val_depositado * 0.007;
    rendimento = val_depositado + tx_juros;
    printf("Este e o valor apos o rendimento de um mes %.2f", rendimento);

    return 0;
}

/*ler o valor de x e  resolver a função y = 2* V x+1 / (3x3) */
int main() {
     double x, y ;
    printf("Digite um número: ");
    scanf("%1f",&x);
    y = (2 * sqrt(x+1))/ (3 * (pow(x,3)));
    printf("resultado a fórmula: %f", y);
    return 0;
}

/*çer um ângulo em graus, convertê-lo para radianos e mostrar o seno e consseno*/
int main() {
    float angulo;
    printf("Digite um angulo em graus: ");
    scanf("%f",&angulo);
    angulo = angulo * M_PI/180;
    printf("O seno do angulo(%3f) e: %f", angulo, sin(angulo));
    printf("O cosseno do angulo(%f) e: %3f", angulo, cos(angulo));
    return 0;
}
