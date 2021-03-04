# liudazhi
代码

  1 #include <stdio.h>
  2 int main()
  3 {
  4   int i,j;
  5   for(i=1;i<=9;)
  6      {
  7       for(j=1;j<=9;j)
  8          {
  9            if(i>=j)
 10                 {
 11                   printf("%d*%d=%d    ",j,i,j*i);
 12                 }
 13                j++;
 14          }
 15             printf("\n");
 16                i++;
 17          }
 18 
 19 
 20 return 0;
 21 }  
