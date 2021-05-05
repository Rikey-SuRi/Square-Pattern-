# Square-Pattern-
#include<stdio.h>
int main()
{
  int n,a,i,j;
  scanf("%d",&n);
  a=n;
  if(n==5)
    n=4;
  for(i=0;i<n;i++)
  {
      for(j=0;j<a;j++)
      {
        printf("* ");
      }printf("\n");
  }
}
