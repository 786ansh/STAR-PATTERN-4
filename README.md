# STAR-PATTERN-4
#include <stdio.h>

int main()
{
    for(int i=0;i<4;i++)
    {
        for(int j=0;j<4;j++)
        {
            if(i+j<=3)
            {
                printf("*");
                
            }
          
            else 
            printf(" ");


        }
        printf("\n");
    }

    return 0;

}
