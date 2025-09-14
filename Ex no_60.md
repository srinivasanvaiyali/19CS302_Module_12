# EX 60 C function to find the peek element of the queue using linked list.
## DATE:
## AIM:
To write a C function to find the peek element of the queue using linked list.

## Algorithm
1. Start
2. Check if the queue is empty (front == NULL):
     * If empty, print "Queue is empty" and exit.
3. Otherwise, return the data of the front node.
4. End   

## Program:
```
/*
C function to find the peek element of the queue using linked list.

Developed by: SRINIVASAN V
RegisterNumber: 212222043008
*/
```
```
struct Node
{
   int data;
   struct Node *next;
}*front=NULL,*rear=NULL;
void peek()
{
    printf("%c",front->data);
}
```

## Output:

<img width="592" height="573" alt="441058430-2304b47b-6f48-47d2-ada7-d050be32dab5" src="https://github.com/user-attachments/assets/98dbb956-be3c-4747-a2b1-57ba06e181f1" />


## Result:
Thus the program was executed and the output was verified successfully.
