#include <stdio.h>
#include <stdlib.h>
#include <string.h>
#include <math.h>

/*leia um cpf, no formato string e informe se o mesmo tem 11 dígitos ou não. strlen - ver o tamanho em n° da string.*/
int main(){
    char cpf[15];
    int tamanho;
    printf("Digite seu cpf sem pontuação:\n");
    scanf("%s",&cpf);
    tamanho = strlen(cpf);
    if(tamanho==14)
        printf("Seu CPF tem 11 digitos\n");
    else
        printf("Número digitado não corresponde a um CPF.\n");
    return 0;
}

/*verificar se as credenciais são as mesmas armazenadas no banco*/
int main(){
    int conta_banco = 12345678;
    int agencia_banco = 1234;
    int senha_banco = 789;

    int conta, senha, agencia;
    printf("Digite sua conta de banco: \n");
    scanf("%d",&conta);
    printf("Digite o numero da sua agencia: \n");
    scanf("%d",&agencia);
    printf("Digite sua senha: \n");
    scanf("%d",&senha);

    if ((conta_banco == conta) && (agencia_banco == agencia)&& (senha_banco == senha)){
        printf("Credenciais validas");
    }
    else{
        printf("Credencias inválidas");
    }
    system("pause");
    return 0;
}

/*calcular o alcance para ver se atinge ou não um alvo a 300m do canhão e 50m de comprimento*/
int main(){
    float velocidade, alcance, angulo;
    printf("Digite a velocidade de lançamento: \n");
    scanf("%f",&velocidade);
    printf("Digite o ângulo de tiro: \n");
    scanf("%f",&angulo);
    angulo = angulo * M_PI/180;
    velocidade = pow(velocidade,2);
    alcance = (velocidade * sin(2 * angulo))/9.8
    
    if ((alcance>=300)&&(alcance<=350)){
        printf("Alvo atingido");
    }
    else{
        printf("Tente novamente");
    }
    system("pause");
    return 0;
}


