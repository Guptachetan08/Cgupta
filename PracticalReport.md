# Practical Report for Programing for Problam Solving
## Name - CHETAN GUPTA
## ROLL NO.- 1915017
## BRANCH - COMPUTER SCIENCE
## SECTION - CSE(A1)

# PROGRAM NO.1 : PROGRAM TO PRINT WELCOME MESSAGE
`#include <stdio.h>`  
`void main ()`  
`{`  
`puts ("Welcome Budding Engineers");`  
`}`  

## OUTPUT
`Welcome Budding Engineers`

# PROGRAM NO. 2 : PROGRAM TO PRINT THE ADDRESS
`include <stdio.h>`
`void main ()`
`{`
`puts ("House number : 172");`
`puts ("Janta Nagar ");`
`puts ("Malerkotla");`
`}`

## OUTPUT
`House Number : 172`
`Janta Nagar`
`Malerkotla`

# PROGRAM NO 3 : PROGRAM TO FIND THE SUM OF TWO NUMBERS
`#include <stdio.h>`
`int main ()`
`{`
`int a,b,c;`
`printf ("Enter first variable : ");`
`scanf ("%d",&a);`
`printf("Enter second variable : ");`
`scanf ("%d",&b);`
`c = a+b;`
`printf("Sum of two variables is : %d\n",c);`
`return 0;`
`}`

## OUTPUT
`Enter first variable : 10`
`Enter second variable : 20`
`Sum of two variables is : 30`

# PROGRAM NO 4 : PROGRAM TO CONVERT TEMPERATURE FROM CELCIUS TO FAHRENHEIT
`#include <stdio.h>`
`void main ()`
`{`
`float num1,num2;`
`printf ("\nEnter value in centigrade:\n");`
`scanf ("%f",&num1);`
`num2 = (num1*9/5)+32;`
`printf ("\nValue in farenheit is :%.2f\n",num2 );`
`}`

## OUTPUT
`Enter value in centigrade:`
`100`

`Value in farenheit is :212.00`

# PROGRAM NO 5 : PROGRAM TO FIND AREA AND PERIMETER OF A CIRCLE
`#include <stdio.h>`
`int main ()`
`{`
`float radius,area, peri,pi=3.14 ;`
`printf("Enter radius of circle :");`
`scanf ("%f",&radius);`
`area=pi*radius*radius;`
`peri=2*pi*radius;`
`printf("Area of circle : %f,",area);`
`printf("Perimeter of circle : %f",peri);`
`return 0;`
`}`

## OUTPUT
`Enter radius of circle :5`
`Area of circle : 78.500000,Perimeter of circle : 31.400002`

# PROGRAM NO 6 : PROGRAM TO SWAP TWO NUMBERS WITHOUT USING THIRD VARIABLE
`#include <stdio.h>`
`int main ()`
`{`
`int a,b;`
`printf ("\nEnter the value of a :");`
`scanf ("%d",&a);`
`printf("\nEnter the value of b :");`
`scanf ("%d",&b);`
`a=a+b;`
`b=a-b;`
`a=a-b;`
`printf ("\nThe swaped values of a : %d\n",a);`
`printf ("\nThe swaped value of b : %d \n",b);`
`return 0;`
`}`

## OUTPUT
`Enter the value of a :10`

`Enter the value of b :20`

`The swaped values of a : 20`

`The swaped value of b : 10`

# PROGRAM NO 7 : PROGRAM TO CHECK WHETHER THE NUMBER IS EVEN OR ODD
`#include <stdio.h>`
`int oddeven(int num1);`
`int main ()`
`{`
`int s ;`
`printf ("Enter the integer:");`
`scanf ("%d",&s);`
`oddeven (s);`
`return 0;`
`}`
`int oddeven(int num1)`
`{`
`if (num1%2==0)`
`printf ("The number is even");`
`else`
`printf ("The number is odd:");`
`return 0;`
`}`

## OUTPUT
`Enter the integer:177`
`The number is odd`







