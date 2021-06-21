# Number-of-digits-in-any-number-without-using-loop
#include<stdio.h>
#include<math.h>
int main()
{   
    int n,k;
    printf("Please provide a number:\n");
    scanf("%d",&n);
    k=(log(n)/log(10));
    printf("The number of digits are:%d",k+1);
    return 0;
}
