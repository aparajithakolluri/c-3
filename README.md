#include <stdio.h>
int main()
{
    int num[5];
    printf("enter the value of 5 numbers:");
    for(int i=0;i<5;i++){
    scanf("%d",&num[i]);
    }
    printf("the numbers u have");
    for(int i=0;i<5;i++){
        printf("%d \n", num[i]);
    }
     printf("%d \n",num[1]);
     return 0;
     
