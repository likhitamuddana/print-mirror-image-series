# print-mirror-image-series
An integer N is passed as input .The program must print the integers from N to 1 and its mirror image.



#include<stdio.h>

int main()
{
int i,j,n;
scanf("%d",&n);
for(i=n;i>=1;i--)
{
printf("%d\t",i);
}
for(j=2;j<=n;j--)
{
printf("%d\t",j);
}
return 0;
}


input : 6
output : 6 5 4 3 2 1 2 3 4 5 6
