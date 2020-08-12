#include<stdio.h>
int prime(int n)
{
int i,count=0;
for(i=1;i<=n;i++)
{
if(n%i==0)
{
count++;
}
}
if(count==2)
{
return 0;
}
else
{
return 1;
}
}


int main()
{
int m,res;
scanf("%d",&m);
res= prime(m);
if (res==0)
{
    printf("true\n");
}
    else
        {
            printf("false\n");

    }
}
