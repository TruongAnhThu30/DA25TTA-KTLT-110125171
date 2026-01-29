# DA25TTA-KTLT-110125171
#include<stdio.h>

int main()
{
	int a,b;
	int tong=0,hieu=0,tich=1;
	float thuong=1;
	printf("Nhap vao so nguyen a:");
	scanf("%d",&a);
	printf("Nhap vao so nguyen b:");
	scanf("%d",&b);
	
	
	tong=a+b;
	hieu=a-b;
	tich=a*b;
	thuong=a/b;
	printf ("\nTong hai so nguyen la:%d",tong);
	printf ("\nHieu hai so nguyen la:%d",hieu);
	printf ("\nTich hai so nguyen la:%d",tich);
	printf ("\nThuong hai so nguyen la:%.2f",thuong);

	return 0 ;
}
