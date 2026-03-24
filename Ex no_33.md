# EX 33 C program to read a file name from user and create that file using fopen().
## DATE:
## AIM:
To write a C program to read a file name from user and create that file using fopen().

## Algorithm
Start. Define a variables. Write a program to read a file name from user and create that file using fopen(). Read the value using scanf. Ask the user to make an input. Print out the answer. End.

## Program:
```
/*
C program to read a file name from user and create that file using fopen().

#include <stdio.h> 
int main()
{FILE *p;
char name[40]; 
scanf("%s",name);
p=fopen("name","w");
printf("%s File Created Successfully\n",name); 
printf("%s File Opened\n",name);
fclose(p);
printf("%s File Closed",name);
} 
*/
```

## Output:

<img width="1004" height="324" alt="515541755-dbcd0a82-9236-4f8d-ba58-e7b04c620ba5" src="https://github.com/user-attachments/assets/722921ff-61a5-462c-a9ed-6f4be0b06537" />


## Result:
Thus the program was executed and the output was verified successfully.
