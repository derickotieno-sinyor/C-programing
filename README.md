#include <stdio.h>

int main()
{
    const float timeOnlineClass = 10.30;
   printf("What is your time: ");
   scanf("%f",&timeOnlineClass);

   if (timeOnlineClass<=10.30){
       printf(" PLEASE WAIT PATIENTLY...WE ARE RE-DIRECTNG YOU TO YOUR ONLINE CLASS\n");
   }
   else {
       printf (" SORRY YOURE NOT ALLOWED TO JOIN ONLINE CLASS\n");}
       return 0;
   }
