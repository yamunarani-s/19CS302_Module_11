# EX 53 C program to remove duplicates in an array.
## DATE:19/05/25
## AIM:
To write a C program to remove duplicates in an array.

## Algorithm
1. Analyze the question
2. Follow the algorithm
3. Try the code
4. Check for error
5. Run & Display the output
## Program:
```
/*
C program to remove duplicates in an array
Developed by: 
RegisterNumber:  
*/
```
#include <stdio.h>

int removeDuplicates(int arr[], int n) {
    int temp[n];
    int i, j, k = 0;
    int isDuplicate;

    for (i = 0; i < n; i++) {
        isDuplicate = 0;
        for (j = 0; j < k; j++) {
            if (arr[i] == temp[j]) {
                isDuplicate = 1;
                break;
            }
        }
        if (!isDuplicate) {
            temp[k++] = arr[i];
        }
    }

## Output:

1 2 3

## Result:
Thus the program was executed and the output was verified successfully.
