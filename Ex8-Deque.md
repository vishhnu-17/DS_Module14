# Ex 2C Deque
## DATE: 08/03/2025
## AIM:
To write a C function to count the number of elements present in the deque.

## Algorithm
1. Start the program.
2. Include required libraries.
3. Define a function to count the number of elements in the deQueue.
4. Run a loop from zero index to maximum index value and increment count if the value is not equal to zero. Return the counted value.
5. End the program.

## Program:
```
/*
Program to count the number of elements present in the deque
Developed by: Kurapati Vishnu Vardhan Reddy
RegisterNumber: 212223040103
*/

#include<stdio.h>
int count(int *arr) {
  int c = 0, i;
  for(i=0;i<MAX;i++)
  {
      if(arr[i]!=0)
      c++;
  }
  return c;
}
```

## Output:

![image](https://github.com/user-attachments/assets/483ebfec-ec48-4475-adad-037d587fff24)

## Result:
Thus, the C code to count the number of elements present in the deque is implemented successfully.
