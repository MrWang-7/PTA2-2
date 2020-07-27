# PTA2-2
//阶梯电价
#include<stdio.h>
int main()
{
	double A;
	double cost = 99999;
	scanf("%lf",&A);
	printf("%lf\n", A);//测试 
	if (A<=0) {
	 printf("one\n");//测试 
	 printf("Invalid Value!");
	}else {
	    if (0<A<=50) {
	   cost = 0.53 * A;
	   printf("two\n");//测试 
	   printf("cost = %.2f" ,cost);}
	    else 	{
	   cost = A * 0.58 - 2.5;
	   printf("three\n");//测试 
	   printf("cost = %.2f" ,cost);}
	}

    
	return 0;

}
