# EX 8 C program to perform multiplication and division of two numbers using functions (without argument and without return type).
## DATE:
## AIM:
To write a C program to perform multiplication and division of two numbers using functions (without argument and without return type).

## Algorithm
1. Start.
2. Declare the variables.
3. Prompt the user to enter a value.
4. Read the value using scanf.
5. Enter number for multiplication and division. 
6. End.  

## Program:
```
/*
Program to perform multiplication and division of two numbers using functions (without argument and without return type).
Developed by: SRINIVASAN V
RegisterNumber: 212222043008 
*/
```
```
#include<stdio.h> 
void multiply(int a,int b); 
void div(int a,int b); 
int main () 
{ 
int a,b; 
scanf("%d%d",&a,&b); 
multiply(a,b); 
div(a,b); 
} 
void multiply(int a,int b) 
{ 
int product; 
product= a*b; 
printf("Multiplication: %d",product); 
} 
void div(int a,int b) 
{ 
int result; 
result=a/b; 
printf("\nDivision: %d",result); 
}
```

## Output:
<img width="597" height="195" alt="442651383-39e6c107-f059-4e5f-b7af-2c60ddb1d99f" src="https://github.com/user-attachments/assets/36f19f61-137e-48c9-9557-5cc13cad98b8" />



## Result:
Thus the program was executed and the output was verified successfully.
