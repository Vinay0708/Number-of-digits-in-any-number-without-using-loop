# Number-of-digits-in-any-number-without-using-loop
#include<stdio.h>
#include<math.h>
int main()
{   
    int n;
    printf("Please provide a number:\n");
    scanf("%d",&n);
    n=(log(n)/log(10));
    printf("The number of digits are:%d",n+1);
    return 0;
}
