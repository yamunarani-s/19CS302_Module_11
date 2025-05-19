# EX 51 C program to reverse a string.
## DATE: 19/05/25
## AIM:
To write a C program to reverse a string.

## Algorithm
1. Analyze the question
2. Follow the algorithm
3. Try the code
4. Check for error
5. Run & Display the output
## Program:
```
/*
C program to reverse a string.
Developed by: 
RegisterNumber:  
*/
```
#include <stdio.h>
#include <string.h>

void reverseString(char *str) {
    int start = 0;
    int end = strlen(str) - 1;
    char temp;

    while (start < end) {
        temp = str[start];
        str[start] = str[end];
        str[end] = temp;
        start++;
        end--;
    }
}
## Output:
olleh


## Result:
Thus the program was executed and the output was verified successfully.
