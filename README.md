# Abcdtri
#include<stdio.h>
void main()
{
int n,a;
printf("Enter any number ");
scanf("%d",&n);
a=65;
for(int I=1;I<=n;I++)
{
for (int j=1;j<=n+1-I;j++)
{
if(I==1 || j==1 || I==n ||j==n+1-I )
printf("%c ",a++);
else
printf("  ");
}
printf("\n");
}
}
    
