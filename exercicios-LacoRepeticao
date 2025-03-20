#include <stdio.h>
#include <stdlib.h>
#include <string.h>
#include <math.h>
#include <time.h>

/*mostrar os números de 5 a 50, variando de 5 em 5.*/
int main( ){
     int i; 
     for(i=5;i<=50;i+=5){
          printf(“%d\n”,i);
     }
     return 0;
}

/*ler um valor e mostrar a sequência de fibonacci até a quantidade desse valor.*/
int main( ){
     int i = 1, num, proximo, anterior, atual;
     printf(Digite a qtd de termos:\n”);
     scanf(“%d”,&num);
     anterior =1; 
     atual =1;
     printf(“%d  %d”,anterior, atual);
     while(i<=num){
             proximo = anterior+atual;
             printf(“%d\t”,proximo);
             anterior = atual;
             atual = proximo;
             i++;
}
    return 0;
}

/*fatorar um número lido, o número está entre 1 e 7.*/
int main( ){
     int num, fatorial;
     do{
         fatorial =1;
         printf(“Digite um n° entre 1 e 7:\n”);
         scanf(“%d”%,&num);
         if((num>=1)&&(num<=7)){
            for(int i =1; i<=num,i++){
                fatorial = fatorial*i;
                printf(“%d\t”,fatorial);
               }
         }
         else{
               printf(“Digite apenas n° entre 1 e 7 \n”);
               printf(“\n”);
         }
   }while((num<1) || (num>7));
     return 0;
}

/*gerar um número aleatório e pedir para o usuário acertar em 5 tentativas e exibir mensagens na tela conforme as tentativas*/
int main(){
    int num, guessNum,i=1;
    srand(time(NULL));
    //tenho que declarar a geracao do numero fora do loop
    num = rand()%10;
    printf("Voce tera 5 tentativas para adivinhar o numero\n");
    do{
        printf("Digite um numero entre 0 e 9: \n");
        scanf("%d",&guessNum); //esqueci do & 
        //se colocar tudo dentro do if compromete mais a performance 
        if(guessNum <0 || guessNum >9){
            printf("Digite apenas um valore entre 0 e 9\n");
        }
        else{
                //usei apenas um = o que atribuia, nao comparava
            if(guessNum==num){
                printf("PARABENS!! ADIVINHOU!!\n");
                break; //usar o break para terminar o loop se acertou
            }
        else if (guessNum <num){
                printf("TENTE UM NUMERO MAIOR\n");
            }
              else{
                printf("TENTE UM NUMERO MENOR\n");
            }
        }
        i++; //esqueci de incrementar, ai so rodava uma vez
    }while(i<=5);
    if(i>5){
        printf("VOCE PERDEU, o numero gerado foi %d \n",num);
    }
    return 0;
}

/*mostrar numeros primos de 1 a 50*/
int main( ){
     int i, j, primo;
     for(i=2;i<=50;i++){
          primo =1;
          for(j=2;j<=sqrt(i)+1;j++){
               if(i%j==0)
                 break;
       }
         if (primo == 1)
             printf(“%d\t”,i);
}    
     return 0;
}
