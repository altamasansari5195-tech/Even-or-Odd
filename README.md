# Even-or-Odd
Write a program in C to check the given number is even number or odd number?

#include <stdio.h>

void main()
{
    int num;
    
    printf("enter value:");
   
    scanf("%d",&num);
   
    if(num%2==0)
   {
        printf("even");
    }
    else
    {
    printf("odd");}
}
