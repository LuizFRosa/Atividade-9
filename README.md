# Atividade-9

#include <stdio.h>
#include <stdlib.h>
	
int fat, n; 

int main() {
  
   printf("Digite um numero a ser fatoral: \n");
   scanf("%d", &n);

   for(fat = 1; n > 1; n = n - 1)
   {
   fat = fat * n;
   }

   printf("O valor fatoriado ficou em: \n%d", fat);
   return 0;
}	
