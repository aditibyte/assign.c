#include<stdio.h>
int main()
{
int p=2,q=3 ;
printf("before swap p=%d q=%d" ,p ,q) ;
p=p+q ;
q=p-q;
p=p-q ;
printf("\n after swap p=%d q=%d" ,p ,q) ;
return 0 ;
}
