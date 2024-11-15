#include <stdio.h>
#include <stdlib.h>
int main() 
{

//AREA OF TRIANGLE

float base,height;
printf("Enter base = ");
scanf("%f", &base);
printf("Enter height = ");
scanf("%f", &height);
printf("Area of triangle = %f \n\n", (base*height)/2);

//AREA OF REACTANGLE

float length,breath;
printf("Enter value of length = ");
scanf("%f", &length);
printf("Enter value of breath = ");
scanf("%f", &breath);
printf("AREA OF RECTANGLE = %f \n\n", length*breath);

//AREA OF CIRCLE

float radius;
printf("Enter radius = ");
scanf("%f", &radius);
printf("AREA OF CIRCLE = %f \n \n", 3.14*radius*radius);

//AREA OF SQUARE

float side;
printf("Enter side = ");
scanf("%f", &side);
printf("AREA OF SQUARE = %f \n\n", side*side);

//TO PRINT THE AGE

int age;
printf("ENTER YOUR AGE = ");
scanf("%d", &age);
if (age==18)
{
printf("YOUR AGE IS 18 \n");
printf("you should focus of study frist");
}
else if (age>18)
{
printf("YOU ARE ADULT \n");
printf("AGE = %d \n", age);
}
else if (age<18)
{
printf("you are MINOR \n");
printf("AGE = %d \n", age);
}
return 0;
}
