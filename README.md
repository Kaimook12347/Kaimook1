#include<stdio.h>
main()
{
	int x[100];
	int n,i,min,max;
	printf("Program show max@min number");
	printf("\nEnter N Number :");
	scanf("%d",&n);
	for(i=0;i<n;i++)
	{
		printf("x[%d] =",i+1);
		scanf("%d",&x[i]);
	}
	printf("Minimum =%d\n",min);
	max=x[0];
	for(i=1;i<n;i++)
	{
		if(max<x[i])
		max=x[i];
		
	}
	printf("Maximum =%d",max);
	min=x[0];
	for(i=1;i<n;i++)
	{
		if(min>x[i])
		min=x[i];
		
	}
}
