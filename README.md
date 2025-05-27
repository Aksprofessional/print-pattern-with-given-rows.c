# print-pattern-with-given-rows.c
// Online C compiler to print pattern with given rows // example enter no. of rows=8 Z ZY ZYX ZYXW ZYXWV ZYXWVU ZYXWVUT ZYXWVUTS 
// Online C compiler to print pattern with given rows
// example enter no. of rows=8
Z
ZY
ZYX
ZYXW
ZYXWV
ZYXWVU
ZYXWVUT
ZYXWVUTS

#include <stdio.h>

int main() {
    int i,j,n;
    printf("enter no. of rows=");
    scanf("%d",&n);
    for(i=0;i<n;i++)
    {
        for(j=0;j<=i;++j)
        printf("%c",90-j);
        printf("\n");
    }
    return 0;
}
