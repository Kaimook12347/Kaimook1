#include<stdio.h>
int square(int a);
main()
{
	int n[5]={1,2,3,4,5};
	for(int i=0;i<5;i++)
	{
		printf("%d\n",square(n[i]));
	}
	
}

int square(int a)
{
	int r;
	r=a*a;
	return r;
}
