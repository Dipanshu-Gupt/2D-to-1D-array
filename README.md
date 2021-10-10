# 2D-to-1D-array-conversion
#include <stdio.h>

int main()
{
    int i = 0;
    int a[3][3] = {{92,88,4},{6,10,36},{96,66,83}};
    int *b;
    b=&a[0][0];
    for(i=0; i< 9; i++){
      printf("%d ", b[i]);
    }
    return 0;
 }
