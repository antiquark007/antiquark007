//matrix multiplication
#include <stdio.h>

int main() 
{
    int i,j,k,m,n,p,q,a[100][100],b[100][100],c[100][100];
    printf("enter number of row");
    scanf("%d",&m);
    printf("enter number of column");
    scanf("%d",&n);
    printf("enter number of row");
    scanf("%d",&p);
    printf("enter number of column");
    scanf("%d",&q);
    
    for (i=0;i<m;i++)
    {
        for(j=0;j<n;j++)
        {
            printf("enter element of matix row wise");
            scanf("%d",&a[i][j]);
        }
    }
    for (i=0;i<m;i++)
    {
        for(j=0;j<n;j++)
        {
            printf("enter element of matix row wise");
            scanf("%d",&b[i][j]);
        }
    }
    if(m!=q)
    printf("multiplication can't happen");
    else
    for(i=0;i<m;i++)
    {
        for(j=0;j<q;j++)
        {
            for(k=0;k<n;k++)
            {
                c[i][j]=c[i][j]+a[i][k]*b[k][j];
            }
        }
    }
    for (i=0;i<m;i++)
    {
        for(j=0;j<n;j++)
        printf("%d\t",c[i][j]);
        printf("\n");
    }
    return 0;
}