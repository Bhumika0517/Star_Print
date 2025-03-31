// # Star_Print
// Star Printing according to user's input.
#include <stdio.h>
int main()
{
    int num, i;
    printf("Enter the number of rows = ");
    scanf("%d", &num);
    while(num>0){
        printf("\n");
        i = 1;
        while (i<=num)
        {
            printf("*");
            i++;
        }
        num = num-1;
    }
    return 0;
}
