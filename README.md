# array-of-element-check-odd-even


#include<stdio.h>
void main()
{
	int a[10],n,i;
	printf("enter number:\n");
	for(i=0;i<10;i++)
	scanf("%d",&a[i]);
	for(i=0;i<10;i++)
	{
	if(a[i]%2==0)
	printf("even");
	else
	printf("odd");
	}
	getch();
	
}
