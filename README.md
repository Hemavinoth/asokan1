#include<stdio.h>
#include<conio.h>
{
int i flag=0;
printf("enter no");
scanf("%d",&n);
for(i=2;i<=n/2)
{
if(n/i==0)
{
flag=1;
break;
}
}
if(flag==0)
{
printf("prime",n);
else
printf("not prime",&n);
}
return 0;
}
