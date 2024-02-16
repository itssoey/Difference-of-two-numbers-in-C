# Difference-of-two-numbers-in-C

#include<stdio.h>
 
int main()
{
    int x,y;
    int diff;
 
    printf("Enter first number: ");
    scanf("%d",&x);
    printf("Enter second number: ");
    scanf("%d",&y);
 
    if(x>y)
        diff=x-y;
    else
        diff=y-x;
 
    printf("\nDifference between %d and %d is = %d",x,y,diff);
    return 0;
}
