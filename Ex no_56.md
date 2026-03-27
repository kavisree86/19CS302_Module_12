# EX 56 C function to display stack elements using Linked List.(store integer data in stack) .
## DATE:
## AIM:
To write a C function to display stack elements using Linked List.

## Algorithm
Start.
Define a variables.
Write a program to display stack elements using linked list.
Read the value using scanf.
Ask the user to make an input.
Print out the answer.
End  

## Program:
```
/*
C function to display stack elements using Linked List.(store integer data in stack) .

Developed by: 
RegisterNumber:  
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

<img width="769" height="500" alt="image" src="https://github.com/user-attachments/assets/5d7aab3c-5068-4e21-9700-d00eee2b8630" />


## Result:
Thus the program was executed and the output was verified successfully.
