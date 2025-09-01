# -program-to-calculate-the-simple-interest.

 #include <stdio.h>
int main()
{
  float p,r,t,si;
  
  printf("enter p\n");
  scanf("%f", &p);
  
  printf("enter r\n");
  scanf("%f", &r);
  
  printf("enter t\n");
  scanf("%f", &t);
  
  si=p*r*t/100;
  
  printf("simple interest %f" , si);
}
