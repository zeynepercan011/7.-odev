# 7.-odev

/*veri als�n ama d�nd�rmesin. r al�n�p alan. dairenin. */

#include<stdio.h>
#define PI 3.14
void alan(double a);

int main(void)
{
	double y;
	printf("yaricap giriniz:");
	scanf("%lf" , &y);
	alan(y);
	return 0;
}

void alan(double a)
{
	double sonuc;
	sonuc=PI*a*a;
	printf("alan=%5.2lf" , sonuc);
}
