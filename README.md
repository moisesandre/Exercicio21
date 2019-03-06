# Exercicio21

#include <stdlib.h>
#include <stdio.h>

int main()
{
  system("color 0b");
  int n, fatorial;

   while(n>=1)
  {
    printf("Digite um valor: ");
    scanf("%d",&n);

    if (n>=1)
    {
    for (fatorial=1; n>1;n=n-1)
    {
        fatorial=fatorial*n;
    }
    printf("O fatorial e %d\n",fatorial);
  }
  }
  return 0;
}
