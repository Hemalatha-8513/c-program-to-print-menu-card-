c program to print a menu card
#include<stdio.h>
main ()
{
	int choice=0;
	printf("pick an item:\n 1.pizza,\n 2.burger,\n 3.pasta,\n 4.french fries");
	scanf("%d,&choice");
	switch(choice)
	{
		case1:
			printf("food item-pizza");
			printf("\n price-rs 239");
			break;
		case2:
			printf("food item-burger");
			printf("\n price-rs 129");
			break;
		case3:
			printf("food item-pasta");
			printf("\n price-rs 99");
			break;
		cae4:
			printf("food item-frenchfries");
			printf("\n price-rs 149");
			break;
		default:
			printf("invalid choice");
	}
	
}
