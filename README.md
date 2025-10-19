# Program-3D
C module 3
EX NO-3)D)a c program to count total number of positive elements in an array
DATE:19/10/25
NAME:JADE ADRINA J
REF NO:25017000
AIM:TO Write a c program to count total number of positive elements in an array
ALGORITHM:
1)Take a array as input from user using scanf().2) iterating the array using for loop.3)check if an element is greater than 0 .4) add 1 to c .5) print the total number of positive numbers(c) using printf() function.
PROGRAM:
```
#include<stdio.h>
int main()
{
    int n,i,c=0;
    scanf("%d",&n);
    int a[n];
    for(i=0;i<n;i++)
    {
        scanf("%d",&a[i]);
    }
    for(i=0;i<n;i++)
    {
        if(a[i]>=0)
        {
            c=c+1;
        }

    }
    printf("count  of positive numbers  in array: %d",c);
}
```
OUTPUT:
<img width="1137" height="207" alt="Screenshot 2025-10-19 222749" src="https://github.com/user-attachments/assets/8caac83f-4fcd-46a0-952a-ce886a650a06" />
RESULT:
Thus, a c program to count total number of positive elements in an array has been successfully executed.

