#include<stdio.h>
int main()
{
int c,p,j,am=0;
scanf("%d%d",&c,&p);
while(c>0)
{
am=am+c;
c=c-((c*p)/100);
}
printf("%d",am);
return 0;
}
