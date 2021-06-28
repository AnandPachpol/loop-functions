#include<stdio.h>
#include<conio.h>
int sum(int s);
int main()
{	
	int x;
	printf("Input number:\n");
	scanf("%d",&x);
	printf("Sum of digits : %d",sum(x));
	getch();
}
int sum(int s)
{
	if(s==0)
	{
		return 0;
	}
	else
	{
		return(s%10+sum(s/10));
	}
}
