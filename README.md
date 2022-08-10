#include <stdio.h>

int main()
{
int n,sum=0,temp,HN,r;
scanf("%d",&n);
temp=n;
while(n>0)
{
    r=n%10;
    sum=sum+r;
    n=n/10;
}
if(temp%sum==0)
printf("Harshad Number");
else
printf("Not Harshad Number");
    return 0;
}
