#include<stdio.h>
int main()
{
int a;
short b;
char c;
float d;
double e;

printf("Number : 200210328,\nName : 喻李齐,\nSubject No.1-program No.1");         /*打印个人信息*/
printf("\n\n");

printf("Please input int a : ");
scanf("%d",&a);                                                                                                       /*输入int型变量*/
printf("int a = %d,size of int is %d.\n\n",a,sizeof(int));

printf("Please input short b : ");
scanf("%hd",&b);                                                                                                      /*输入short型变量*/
printf("short b = %hd,size of short is %d.\n\n",b,sizeof(short));

printf("Please input char c : ");
scanf(" %c",&c);                                                                                                         /*输入char型变量*/
printf("char c = %c,size of char is %d.\n\n",c,sizeof(char));

printf("Please input float d : ");
scanf("%f",&d);                                                                                                          /*输入float型变量*/
printf("float d = %f,size of float is %d.\n\n",d,sizeof(float));

printf("Please input double e :");
scanf("%lf",&e);                                                                                                         /*输入double型变量*/
printf("double e = %lf,size of float is %d.\n\n",e,sizeof(double));
return 0;
}
