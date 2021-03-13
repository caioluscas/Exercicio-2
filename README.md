# Exercicio-2
/*Programa: criar um programa que solicite 2 numeros inteiros e imprima:  A sua soma, multiplicação, divisão e informe o   resto da operação entre o 1 e o segundo.*/

#include<stdio.h>
 main()
{int n1, n2,soma,mult,div;


printf("Digite seu primeiro numero:");
scanf("%d",&n1);
printf("Digite o seu segundo numero: ");
scanf("%d",&n2);
soma=n1+n2;
mult=n1*n2;
div=n1/n2;
printf("Sua soma e de: %d \n",soma);
printf("Sua diviso é de: %d \n",div);
printf("Sua multiplicacao e de: %d \n",mult);

}
