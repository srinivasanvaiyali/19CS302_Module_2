# EX 7 C Program to Print a right triangle star Pattern
## DATE:
## AIM:
To write a C Program to Print a right triangle star Pattern

## Algorithm
1. Start.
2. Declare the variables i,j,k,n.
3. Prompt the user to enter a value.
4. Read the value using scanf.
5. Enter number of rows and columns. 
6. End.

## Program:
```
/*
Program to Print a right triangle star Pattern
Developed by: SRINIVASAN V
RegisterNumber: 212222043008 
*/
```
```
#include <stdio.h> 
int main() { 
    int i, j, rows; 
    scanf("%d", &rows); 
    for (i = 1; i <= rows; i++) { 
        for (j = 1; j <= i; j++) { 
            printf("*"); 
        } 
        printf("\n"); 
    }    return 0; 
}
```


## Output:
<img width="333" height="163" alt="442649959-18508b97-4a8a-41b1-920f-cc2fb4f997c0" src="https://github.com/user-attachments/assets/17e7270b-6412-4605-b68b-6a94e6b80016" />



## Result:
Thus the program was executed and the output was verified successfully.
