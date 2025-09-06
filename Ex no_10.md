# EX 10 C program to find the factorial of a given number using a function with arguments and return type.
## DATE:
## AIM:
To write a C program to find the factorial of a given number using a function with arguments and return type.

## Algorithm
1. Start.
2. Declare the variables.
3. Prompt the user to enter a value.
4. Read the value using scanf.
5. Enter factorial of the number.
6.  End. 

## Program:
```
/*
Program to find the factorial of a given number using a function with arguments and return type.
Developed by: SRINIVASAN V
RegisterNumber: 212222043008 
*/
```
```
#include <stdio.h> 
int main() { 
    int n, i; 
    unsigned long long factorial = 1; 
    scanf("%d", &n); 
 
    if (n < 0) { 
        printf("Factorial is not defined for negative numbers.\n"); 
    } else { 
        for (i = 1; i <= n; i++) { 
            factorial *= i; 
        } 
        printf("Factorial of %d = %llu\n", n, factorial); 
    } 
    return 0; 
}
```

## Output:

<img width="518" height="199" alt="442654323-6d13c1bf-84a0-4317-9f80-97810dacdd0d" src="https://github.com/user-attachments/assets/59f51934-fe15-45bc-b29e-60ce3da2fc87" />


## Result:
Thus the program was executed and the output was verified successfully.
