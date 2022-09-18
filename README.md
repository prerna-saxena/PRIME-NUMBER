# PRIME-NUMBER
A NUMBER WHICH COMES IN ITSLEF TABLE ARE PRIME NUMBER


Online C compiler to run C program online
#include <stdio.h>

int main() {
    int n, i, m=0, flag=0;
    printf("ENTER THE NUMBERS TO CHECK PRIME\n");
    scanf("%d", &n);
    for(i=2; i<n/2; i++)
    {
        if (n%i==0)
        {
            printf("no is not prime");
            flag=1;
            break;
        }
    }
    if (flag==0)
    printf("no i prime");
    return 0;
}
