# EX 56 C function to display stack elements using Linked List.(store integer data in stack) .
## DATE:
## AIM:
To write a C function to display stack elements using Linked List.

## Algorithm
1. Start.
2. Define a variables.
3. Write a program to display stack elements using linked list.
4. Read the value using scanf.  
5. Ask the user to make an input.
6. Print out the answer.
7. End

## Program:
```
/*
C function to display stack elements using Linked List.(store integer data in stack) .

Developed by: SRINIVASAN V
RegisterNumber: 212222043008 
*/
```
```
Struct Node 
{ 
float data; 
struct Node *next; 
}*head; 
void display() 
{ 
struct Node *temp= head; 
while(temp!=NULL) 
{ 
printf("%.2f\n",temp->data); 
temp=temp->next; 
} 
 
}
```

## Output:
<img width="769" height="500" alt="441056064-febd2b64-c8eb-4dda-bc3a-ad746a67ac5b" src="https://github.com/user-attachments/assets/16d6743e-cc6c-4358-bbe2-cb15e313f281" />



## Result:
Thus the program was executed and the output was verified successfully.
