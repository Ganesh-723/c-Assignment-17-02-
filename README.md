#include<stdio.h>
main()
{
    int i=1,f=1,n;
    printf("enter the value of n\n");
    scanf("%d",&n);
    while(i<=n)
    {
        f=f*i;
        i++;
    }
    printf("factorial=%d",f);
}
