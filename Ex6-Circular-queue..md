# Ex 2A Dequeue Elements from Circular Queue
## DATE: 03/03/2025
## AIM:
To write a C program to delete three elements from the filled circular queue.

## Algorithm
1. Start the program.
2. Include the required libraries.
3. Check if the queue is empty and return if it is.
4. Follow the deletion logic for circular queue and return the deleted element.
5. End the program

## Program:
```
/*
Program to delete three elements from the filled circular queue
Developed by: Kurapati Vishnu Vardhan Reddy
RegisterNumber: 212223040103
*/

int deQueue() {
    int element;
    if(isEmpty())
    {
        printf("Queue is empty\n");
        return -1;
    }
    else
    {
        element = items[front];
        if(front==rear)
        {
            front=-1;
            rear=-1;
        }
        else
        {
            front=(front+1)%SIZE;
        }
        return element;
    }
}
```

## Output:

![image](https://github.com/user-attachments/assets/356a82ca-fd0f-4060-ac12-87adc29dd5b9)

## Result:
Thus, the C program to delete three elements from the filled circular queue is implemented successfully.
