#include<stdio.h>

int main()
{
    int i,n,a[i],c=0;
    scanf("%d",&n);
    for(i=0;i<5;i++)
    {
        scanf("%d",a[i]);
    }
    for(i=0;i<5;i++)
    {
        if(a[i]==n)
        {
            c=1;
            break;
        }
        
    }
    if(c==1)
    {
        printf("%d",i);
    }
    else
    {
        printf("-1");
    }
    
}
