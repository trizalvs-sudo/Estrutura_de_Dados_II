Faça um programa em C que receba dois números informados pelo usuário e apresente a multiplicação destes números. Atenção, ao apresentar a saída dos dados, apresente a operação junto com o resultado. Exemplo: 5 * 2 = 10

Use a IDE de sua preferência, faça o que se pede, depois copie o código e cole aqui. Não use imagens na sua resposta.

Resposta


//Questão 1 



#include <stdio.h>



int main() {

   int num1, num2;

   int resultado;



   printf("Digite o primeiro numero: ");

   scanf("%d", &num1);



   printf("Digite o segundo numero: ");

   scanf("%d", &num2);



   resultado = num1 * num2;



   printf("%d * %d = %d\n", num1, num2, resultado);



   return 0;

} 
Com essa atividade, aprendi os conceitos básicos da linguagem C e sua relação com Estrutura de Dados I. Utilizei variáveis do tipo int para armazenar números inteiros e organizei o programa em uma sequência lógica de instruções.
