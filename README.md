#include<stdio.h>

int main()
{
	int a;  // cqlo chislo pri 4
	int b; // ostatak pri delene na 4
	int c;    // cqlo chislo pri 100
	int d;    // ostatak pri 100
	int e;    // cqlo chislo pri 400
	int f;    // ostatak pri 400
	int Year;

	printf("Year:");
	scarf_s("%d", Year);

	a = Year / 4;
	Year = a * 4 + b;
	c = Year / 100;
	Year = c * 100 + d;
	e = Year / 400;
	Year = e * 400 + f;


	if ((b = 0 || f = 0) && d != 0)
	{
		printf("Yes");
	}
	else
	{
		printf("No");
	}
	system("pause");
}
