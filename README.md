#include <stdio.h>
#include <stdlib.h>
#include <conio.h>
int main(int argc, char *argv[])
{
   float a, b, c, media;
   float nota, mp ;
   {
printf ("\t\t\t\t\t***CALCULAR MEDIA DA UNEB/EAD***\n\t\t\t\t\t###CRIADA POR MOABE SOUZA###\n");

   }
   system("color 1f");

   printf ("DIGITE A NOTA DO MEIO 1: ");
   scanf ("%f",&a);
   printf ("DIGITE A NOTA DO MEIO 2: ");
   scanf ("%f",&b);
   printf ("DIGITE A NOTA DO MEIO 3: ");
   scanf ("%f",&c);
   media =(a*2 + b*6 + c*2)/10;
   
   printf("Resultado: %.2f\n",media);
   
   if (media >=7) 
         {                                                              
            printf ("VOCE FOI APROVADO ");
            getch();                             
         }
   else
          { 
               printf ("VOCE FOI REPROVADO \n");
               
               
	printf ("\nDIGITE POSSIVEL NOTA DA PROVA FINAL: ");
   scanf ("%f",&nota);
   mp = (media*7 + nota*3)/10;
   
    if (mp >= 5)
    {
    	printf("APROVADO NA FINAL: %.2f\n",mp);
	}
	else
	{
    	printf("REPROVADO NA FINAL: %.2f\n",mp);
    	
	}
	getch();
           }
    system("PAUSE");
	return 0;                    
}
