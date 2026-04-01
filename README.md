#include<stdio.h>
int main(){
int a, b, c;

printf(“25331a05d7\n”);
printf("enter three nos: \n");
scanf("%d %d %d", &a, &b, &c);

if(a > b && a > c){
  printf("a is largest:%d\n", a);
}else{
    if(b > c){
printf("b is largest:%d\n", b);
}else{
printf("c is largest:%d\n", c);
}
}
return 0;
}
