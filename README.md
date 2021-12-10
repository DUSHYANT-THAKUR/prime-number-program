/******************************************************************************

Welcome to GDB Online.
GDB online is an online compiler and debugger tool for C, C++, Python, PHP, Ruby, 
C#, VB, Perl, Swift, Prolog, Javascript, Pascal, HTML, CSS, JS
Code, Compile, Run and Debug online from anywhere in world.

*******************************************************************************/
#include<stdio.h>
#include<conio.h>
void main()
{
    int n,i,result;
    printf("enter the number");
    scanf("%d",&n);
    for(i=2;i<n/2;i++)
    {
    if(n%i==0)
    {
        result=0;
    }
    
    }
    if(result==0)
    {
        printf("number is not prime");
    }
        else
        {
            printf("number is  prime");
    }
    getch();
}
