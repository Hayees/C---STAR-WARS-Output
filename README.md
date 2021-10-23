# C---STAR-WARS-Output
Using the C language. The program will use printf to create a 'STAR WARS' output.
#include <stdio.h>
//Function-ed both "STAR" and "WARS" for future needs.
void star(){
 printf(" 8888888888 888 88888\n");
 printf(" 88 88 88 88 8 88\n");
 printf(" 8888 88 88 88 88888 \n");
 printf(" 88 88 888888888 8 88\n");
 printf("88888888 88 88 88 8 888888\n");
}
void wars(){
 printf("88 88 88 888 88888 888888\n");
 printf("88 88 88 88 88 88 88 88\n");
 printf("88 8888 88 88 88 88888 8888\n");
 printf(" 888 888 888888888 88 88 88\n");
 printf(" 88 88 88 88 88 8888888\n");
}
int main()
{
 star();//Output "STAR"
 printf("\n");//spacing
 wars();//Output "WARS"
 return 0;
}
