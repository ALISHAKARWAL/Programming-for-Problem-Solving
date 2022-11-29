## Program 15: Write a program to concat two strings

#include <stdio.h>

#include <string.h>

int main () 

{

  char string1[10] = "Ali";
     
  char string2[10] = "sha";
     
  strncat(string1,string2,4);
     
  printf("Concatenated string: %s", string1);

     
}

**OUTPUT:Concatenated string: Alisha**
