# EX 34 C program to read a file name from user and create that file and insert student roll numbers in to that file.
## DATE:
## AIM:
To write a C program to read a file name from user and create that file and insert student roll numbers in to that file.

## Algorithm
Start. Define a variables. Write a program to read a file name from user and create that file and insert student roll numbers in to that file. Read the value using scanf. Ask the user to make an input. Print out the answer. End.

## Program:
```
/*
C program to read a file name from user and create that file and insert student roll numbers in to that file.

#include <stdio.h> 
int main()
{
FILE *p;
char name[100]; 
int num;
int id;
char text[100]; 
float m; 
scanf("%s",name);
scanf("%d",&num);
p=fopen("name","w"); 
printf("%s Opened\n",name);
{
scanf("%d %s %f",&id,text,&m); 
fprintf(p,"%d %s %f",id,text,m);
}
fclose(p);
printf("Data added Successfully");
}
*/
```

## Output:

<img width="1266" height="321" alt="515542156-1778eae3-2bc7-41e0-a7a0-f3c16908c85a" src="https://github.com/user-attachments/assets/c14cab39-f3df-4f82-8503-dfff8ce9c99b" />


## Result:
Thus the program was executed and the output was verified successfully.
