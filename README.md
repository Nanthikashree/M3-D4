# M3-D4
AIM:
Write a C program to search an element in an array 
PROGRAM:
```
#include <stdio.h>
int main()
{
    int n,i;
    scanf("%d",&n);
    int a[n];
    for(i=0;i<n;i++)
    {
        scanf("%d",&a[i]);
    }
    int b=5;
    for(i=0;i<n;i++)
    {
        if(a[i]==b)
        {
            printf("%d is found at position %d",b,i+1);
        }
    }
}
```
OUTPUT:
<img width="1015" height="326" alt="image" src="https://github.com/user-attachments/assets/70a1fe7f-374f-4a2d-b11b-082302a6352e" />
RESULT:
Thus the code run successfully!
