#include<stdio.h>
main()
{
	int age;
	printf("Enter your age:");
	scanf("%d",&age);
	if(age>=18)
	{
	printf("You can apply for a driving licence");
    }
    else
    {
    printf("Sorry! You can not apply for a driving licence");	
	}
}
