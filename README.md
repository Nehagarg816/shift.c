# shift.c
this is a program for left and right shift operator.
#include<stdio.h>
#include<conio.h>
void main()
{
	int a,b;
	printf("Enter value of a:");
	scanf("%d",&a);
	b=a>>3;
	printf("Value of b is %d",b);
}
