# Twisted-Minds
To check the palindrome

#include <stdio.h>
#include<conio.h>
void main()
{
int d,a,num;rev=0;
clrscr();
printf(“enter the number”);
scanf(“%d”,&num);
a==num;
while(num>0)
{
d=num%10;
rev=rev*10+d;
num=num/10;
}
if(rev==a)
printf(“palindrome”);
else
printf(“not palindrome”);
getch();
}

1001 is palindrome
1100 is not palindrome 
