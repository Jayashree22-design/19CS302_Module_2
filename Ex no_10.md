# EX 10 C program to find the factorial of a given number using a function with arguments and return type.
## DATE:
## AIM:
To write a C program to find the factorial of a given number using a function with arguments and return type.

## Algorithm
1. Start the program.
2. Take input of the number n from the user.
3. Define a function that takes an integer as an argument and returns the factorial of that number.
4. Call the factorial function with n and store the result.
5. Print the factorial and end the program.
   

## Program:
```
/*
Program to find the factorial of a given number using a function with arguments and return type.
Developed by: JAYASHREE S
RegisterNumber:  212223060103

#include <stdio.h>

int factorial(int n) {
    int fact = 1, i;
    for(i = 1; i <= n; i++) {
        fact *= i;
    }
    return fact;
}

int main() {
    int n, result;
    scanf("%d", &n);
    result = factorial(n);
    printf("%d\n", result);
    return 0;
}

*/
```

## Output:

![444984948-faf96b99-536e-42af-8979-e2cb470197b8](https://github.com/user-attachments/assets/4aac1bb8-3254-4c13-8006-8c337b895f83)


## Result:
Thus the program was executed and the output was verified successfully.
