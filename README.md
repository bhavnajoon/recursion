# recursion
#include<stdio.h>
int sum(int)
int main()
{
   int n,r;
   printf("enter the value of n");
   scanf("%d",&n);
   r=sum(n);
   printf("sum of digits is %d\n",r);
   return 0;
}
int sum(int n)
{
   if(n!=0)
   {
      return(n%10+sum(n/10));
   }
   else
   {
      return 0;
   }
}   
   
