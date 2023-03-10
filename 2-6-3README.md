#include <stdlib.h>  
#include <stdio.h>  
int main(void) {

 int inx, iny,x=100,y=100;
 scanf("%d %d", &inx,&iny);
 inx = abs(inx); iny = abs(iny);
 printf((inx <= x && iny <= y) ? "inside\n" : "outside\n");
}
