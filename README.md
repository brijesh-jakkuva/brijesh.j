
#include<stdio.h>
#include<stdlib.h>
int main()
{
   int num,dis,sum=0;
   scanf("%d %d",&num,&dis);
   dis=100-dis;
   while(num>0)
   {
       sum=sum+num;
       num=(dis*num)/100;
   }
   printf("%d",sum);
   return 0;
}
