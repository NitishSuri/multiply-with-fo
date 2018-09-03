# multiply-with-fo
//11 th program on c
#include<stdio.h>
int main()
{
int i,num1,num2,result=0;
printf("Enter 1st number \n");
scanf("%d",&num1);

printf("Enter 2nd number \n");
scanf("%d",&num2);

for(i=0;i<num1;i++)
{
result=result+num2;
}
printf("The product is %d \n",result);
return(0);
}
