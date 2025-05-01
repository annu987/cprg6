#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    int u;
    scanf("%d",&u);
    int t=0;
    if(u<100)
        t=u*6;
    if(u>100&&u<=200)
        t=100*6+(u-100)*8;
    if(u>200&&u<=300)
        t=100*6+100*8+(u-200)*10;
    if(u>300&&u<=400)
        t=100*6+100*8+100*10+(u-300)*12;
    if(u>400)
        t=100*6+100*8+100*10+100*12+(u-400)*14;
    printf("%d",t);
    return 0;
}
