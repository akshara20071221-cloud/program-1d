# program-1d
###EX-1)d) Find whether the given character is a vowel or not.
**Date:**27/1/2026
**Name:**Akshara.K
**ref.no:**25003090AIM
---
###AIM:Write a C program to check whether the given character is a vowel or not.
---
###ALGORITHM:
1)Get a character input from the user. 2)Check whether it is vowel or not using if else statement. 3)Print the result using printf() function.
---
### PROGRAM

```
#include<stdio.h>
int main()
{
    char ch;
    scanf("%c",&ch);
    if((ch>='a' && ch<='z') || (ch>='A' && ch<='Z'))
    {
        if(ch=='a'||ch=='e'||ch=='i'||ch=='o'||ch=='u'||ch=='A'||ch=='E'||ch=='I'||ch=='O'||ch=='U')
        printf("Vowel.");
        else
        printf("Consonant.");
    }
}
```
###output
<img width="478" height="170" alt="image" src="https://github.com/user-attachments/assets/6cb0cc57-1c9a-4691-a5cd-bab5367255a7" />
###result
the output is executed successfully
