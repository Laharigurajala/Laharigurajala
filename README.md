#include<stdio.h>
void main()
{
    char a[10]="kohli";
    char b[10]="rohit";
    char c[10]="vijay";
    for(int i=0;i<5;i++)
    {
       printf("  %c",a[i]);
    }
    printf("\n");
    for(int i=0;i<5;i++)
    {
       printf("  %c",b[i]);
    }
    printf("\n");
    for(int i=0;i<5;i++)
    {
       printf("  %c",c[i]);
    }
}
output:
 k  o  h  l  i
  r  o  h  i  t
  v  i  j  a  y
Process returned 3 (0x3)   execution time : 1.247 s
Press any key to continue.

