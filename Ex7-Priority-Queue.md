# Ex 2B Priority Queue
## DATE: 03/03/2025
## AIM:
To formulate the C code to display the elements of the priority queue after insertion and deletion operation.

## Algorithm
1. Start the program.
2. Include required libraries.
3. Scan the number of elements to be inserted and deleted.
4. Run loop accordingly and call insert and delete function iteratively.
5. End the program.

## Program:
```
/*
Program to o display the elements of the priority queue after insertion and deletion operation
Developed by: # Ex 2B Priority Queue
## DATE: 03/03/2025
## AIM:
To formulate the C code to display the elements of the priority queue after insertion and deletion operation.

## Algorithm
1. Start the program.
2. Include required libraries.
3. Scan the number of elements to be inserted and deleted.
4. Run loop accordingly and call insert and delete function iteratively.
5. End the program.

## Program:
```
/*
Program to o display the elements of the priority queue after insertion and deletion operation
Developed by: Kurapati Vishnu Vardhan Reddy
RegisterNumber: 212223040103

#include <stdio.h>
int size = 0;
int main() {
    int m,k,e,r,e1;
  int array[10];
  scanf("%d",&m);
  for(k=0;k<m;k++)
  {
      scanf("%d",&e);
      insert(array,e);
  }
  scanf("%d",&r);
  for(k=0;k<r;k++)
  {
      scanf("%d",&e1);
      deleteRoot(array,e1);
  }
  printf("Max-Heap array after insertion and deletion: ");
  printArray(array,size);
}
```

## Output:

![image](https://github.com/user-attachments/assets/e8142f44-e466-4f77-a893-2f1d3211aaaa)

## Result:
Thus, the C program to display the elements of the priority queue after insertion and deletion operation is implemented successfully

RegisterNumber: 212223240020

#include <stdio.h>
int size = 0;
int main() {
    int m,k,e,r,e1;
  int array[10];
  scanf("%d",&m);
  for(k=0;k<m;k++)
  {
      scanf("%d",&e);
      insert(array,e);
  }
  scanf("%d",&r);
  for(k=0;k<r;k++)
  {
      scanf("%d",&e1);
      deleteRoot(array,e1);
  }
  printf("Max-Heap array after insertion and deletion: ");
  printArray(array,size);
}
```

## Output:

![image](https://github.com/user-attachments/assets/e8142f44-e466-4f77-a893-2f1d3211aaaa)

## Result:
Thus, the C program to display the elements of the priority queue after insertion and deletion operation is implemented successfully
