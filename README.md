//# Calculating-the-age-of-the-person-
//Calculating the age of the person whose birth year is entered
#include <stdio.h>
#include <conio.h>
int main(void)
{
    int birthY,year;
    printf("Enter your year of birth: ");
    scanf("%d",&birthY);

    printf("Enter the current year: ");
    scanf("%d",&year);

    year-=birthY;

    printf("\n\nYour age: %d\n",year);
    return 0;

}
