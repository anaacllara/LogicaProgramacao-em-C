#include <stdio.h>
#include <stdlib.h>
#include <math.h>
#include <time.h>

/*ler notas, fazer média e notificar se está aprovado ou não*/
float medArit(float nt1,float nt2,float nt3);
float avalia(float numb1);

int main(){
    float nt1,nt2,nt3, nota, aprov;
    printf("Digite tres notas: \n");
    scanf("%f",&nt1);
    scanf("%f",&nt2);
    scanf("%f",&nt3);

    nota = medArit(nt1,nt2,nt3);
    aprov = avalia(nota);
    
    return 0;
}
float medArit (float num1, float num2, float num3){
    float media = (num1 + num2 + num3)/3;
    printf("A media e %f \n", media);
    return media;
}
float avalia (float numb1){
    if(numb1>6.0){
        printf("Voce esta aprovado(a)\n");
    }
    else{
        printf("Voce esta reprovado(a)\n");
    }
    return 0.0;
}

/*converter graus para radianos*/
float resultado;
void grau(radiano){
    float valor;
    printf("Digite o valor em graus para converter para radianos:\n");
    scanf("%f",&valor);
    resultado = valor * (M_PI/180);
    printf("Conversao de %f para %f \n", valor, resultado);
}
void radiano(grau){
    float valor;
    printf("Digite o valor em radianos para converter para graus:\n");
    scanf("%f",&valor);
    resultado = valor * (180/M_PI);
    printf("Conversao de %f para %f \n", valor, resultado);
}
int main(){
    int escolha;
    printf("Qual conversao voce quer fazer? Graus para radianos - 1\n Radianos para graus 2 \n");
    scanf("%d",&escolha);
    if(escolha ==1) grau();
    else if(escolha ==2) radiano();
    else
        printf("Numero inválido, digite 1 ou 2\n");
    return 0;
}

/*calcular o volume do cubo ou esfera conforme decisão do usuario*/
float calCubo(float aresta);
float calEsfera(float raio);
int main(){
    int escolha;
    printf("Calcular cubo = 1 e calcular a esfera =2. \n Digite sua preferencia\n");
    scanf("%i",&escolha);
    if(escolha ==1){
        float tam, final;
        printf("Digite o tamanho da aresta do cubo: \n");
        scanf("%f",&tam);
        final = calCubo(tam);
        printf("O volume do cubo e %f\n",final);
    }
    else if (escolha ==2){
        float tam, final;
        printf("Digite o tamanho do raio da esfera: \n");
        scanf("%f",&tam);
        final = calEsfera(tam);
        printf("O volume da esfera e %f\n",final);
    }
    else{
        printf("Opção invalida. \n");
    }
    return 0;
}
float calCubo(float aresta){
    float vol = pow (aresta,3);
    return vol;
}
float calEsfera(float raio){
    float vol = (4.0/3.0) * M_PI * pow(raio,3);
    return vol;
}

/*converter um numero decimal (base 10) em binario*/
void converte (int num);
int main(){
    float decimal;
    printf("Digite um numero decimal:\n");
    scanf("%f",&decimal);
    converte(decimal);
    return 0;
}
void converte(int num){
    int binario[32];
    int i =0;
    
    while(num > 0){
        binario[i] = num%2;
        num = num/2;
        i++;
    }
    printf("O valor binário é: ");
    for(int j = i -1; j >-0; j--){
        printf("%d",binario[j]);
    }
    printf("\n");
}

/*Gerar 50 números. criar uma função para comparar com a variável global qual é o maior e uma última função para mostrar a maior variável gerada.*/
int maiorNumero = 0;
void verifica(int num);
void mostra();
int main(){
    int numAleatorio;
    srand(time(NULL));
    for(int i= 0; i<50; i++){
        numAleatorio=rand()%1000;
        verifica(numAleatorio);
    }
    mostra();
    return 0;
}
void verifica(int num){
    if(num>maiorNumero)
          maiorNumero = num;
}
void mostra(){
    printf("O maior numero eh %d\n",maiorNumero);
}

/*escrever uma função que recebe o valor de N e outra para calcular a serie S (1+½+⅓…) a série vai até o valor de N.*/
float valorS(float Nn){
    float i;
    float soma =0;
    for (i=1;i<=Nn;i++)
        soma+=1/i;
    printf("Soma = %f\n", soma);
    return soma;
}
int main(){
    int num;
    printf("Entre com um valor inteiro e positivo: \n");
    scanf("%d",&num);
    valorS(num);
    return 0;
}

/*Calcular o X e o n° de termos desejados para encontrar o cosseno, usando série de taylor*/
void coss(double num, int num2);
double fatorial(int i);
int main(){
    int Xx, termos;
    printf("Digite o valor de X e o numero de termos da serie:\n");
    scanf("%d %d",&Xx,&termos);
    coss(Xx,termos);
    return 0;
}
double fatorial(int i){
    double fat = 1;
    for(int j = 1; j<=i;j++){
        fat*=j;
    }
    return fat;
}
void coss(double num, int num2){
    double cosseno;
    int sinal = -1;
    for(int i = 2; i<=num2 *2; i+=2){
        cosseno +=sinal * (pow(num,i)/fatorial(i));
        sinal *=-1;
    }
    printf("O valor do cosseno e %lf\n",cosseno);
}
