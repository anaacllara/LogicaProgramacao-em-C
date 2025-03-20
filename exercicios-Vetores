#include <stdio.h>
#include <stdlib.h>
#include <math.h>
#include <time.h>

/*gerar 100 n° aleatórios, armazenar num vetor, mostrar na tela e no fim mostrar o maior valor gerado.*/
int main( ){
     int vetor[100];
     int bigvetor=0;
     srand(time(NULL));
     for(int i=1; i<100;i++){
          vetor[i] = rand()%1000;
          printf(“vetor[%d] = %d\t”,i,vetor[i]);
          if(bigvetor<vetor[i])
            bigvetor=vetor[i];
}
      printf(“O maior vetor e %d \n”,bigvetor);
     return 0;
}

/* ler 5 n° e armazenar no vetor A, ler mais 5 e armazenar no vetor B, e juntar tudo no vetor C e mostrar na tela. */
int main( ){
     int vetorA[5];
     int vetorB[5];
     int vetorC[10];
     for(int i=0;i<5;i++){
       printf(“Digite 5 valores, %d/5:\n”,i+1);
       scanf(“%d”,&vetorA[i]);
    }
      for(int j =0;j<5;j++){
        printf(Digite 5 valores, %d/5\n”,j+1);
        scanf(“%d”,&vetorB[j]);
   }
//juntar tudo
      for(int i =0;i<5;i++){
         vetorC[i]=vetorA[i];
     }
     for(int j =0; j<5; j ++){
          vetorC[5+j]=vetorB[j];
    }  
    printf(“Vetor C: \n”);
    for(int k =0;k<10;k++){
         printf(“%d\t”,vetorC[k]);
    }
     return 0;
}

/*ler um nome e imprimí-lo de trás para frente*/
int main( ){
     char nome[20];
     printf(“Digite um nome: \n”);
     scanf(“%s”,&nome);
     strlen(nome);
     for(int i = strlen(nome) - 1; i>=0;i- - ){
         printf(“%c”,nome[i]);
     }
      return 0;
}

/*ler uma frase e printar todas as vogais existentes*/
int main(){
    char vogais[5]= {'a','e','i','o','u'};
    char frase[100];
    printf("Digite uma frase:\n");
    fgets(frase, sizeof(frase),stdin);
    printf("Vogais na frase: ");
    for(int i = 0; i <=strlen(frase); i++){
        for(int j =0; j<5;j++){
            if(frase[i]== vogais[j]){
                printf("%c\t",frase[i]);
                break;
            }
        }
    }
    return 0;
}
