#include <stdlib.h>  
#include <stdio.h>  
int main(void) {
    int num;
    scanf("%d", &num);
    double tmp;
    tmp = (double)num * 1.6;
    printf("%.1f\n", tmp);
    return 0;
}
