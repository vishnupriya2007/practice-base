# practice-base
#include<stdio.h>
int main() {
    int i,j,n,limit;
    printf("enter the limit = ");
    scanf("%d",&limit);
    for (i=1;i<=limit;i++)
    {
        for(j=1;j<=i;j++)
        {
            if((i%3==1))
            {
                printf("#");
            }
            else if ((i%3==2))
            {
                 printf("$");
            }
            else if ((i%3==0) && (j<=i))
            {
                 printf("*");
            }
        }
        printf("\n");
    }  
    
    return 0;
}
