## Program 23: Write program to print table of 5 using goto statement

#include <stdio.h>

int main()

{

int num,i=1;

printf("Enter the number whose table you want to print");

scanf("%d", &num);

table:

printf("%d x %d = %d \n", num,i,num*i);

i++;

if(i<=10)

goto table:

}

**OUTPUT:Enter the number whose table you want to print5**

**5 x 1 = 5**

**5 x 2 = 10**

**5 x 3 = 15**

**5 x 4 = 20**

**5 x 5 = 25**

**5 x 6 = 30**

**5 x 7 = 35**

**5 x 8 = 40**

**5 x 9 = 45**

**5 x 10 = 50**