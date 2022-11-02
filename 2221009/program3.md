#Program to check conditional operator

#include<stdio.h>
int main()
{

int age,a;

printf("enter your age");

scanf("%d",&age);

a=(age>=19)?printf("you can vote"):printf("you cannot vote");

printf("%d",a);

return 0;

}

Output:(if age is 56)

enter your age:(56)

56

you can vote
