#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {

       long int n,r;
    scanf("%ld",&n);
    r=series(n);
    printf("%ld",r);
    return 0;
}
int series(int n)
    {
    int l;
    if(n==1)
        return 3;
    else
    if(n==2)
        return 4;
        else
        {
        if(n%2==0)
            l=4;
        else
            l=3;
        return(10*series((n-1)/2)+l);
    }
}
