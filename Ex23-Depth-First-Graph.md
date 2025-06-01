# Ex 5(C) Depth First Graph
## DATE: 25.04.2025
## AIM:
To compose the code for the function createNode to traverse the graph below in the depth first fashion.

![image](https://github.com/user-attachments/assets/63552824-d0a3-49c6-a473-6db27d1f03e4)

## Algorithm
1. Start
2. Allocate memory for a new node.
3. Set the vertex field of the new node to the given value v.
4. Set the next pointer of the new node to NULL.
5. Return the newly created node.
6. End 

## Program:
```
/*
Program to traverse the graph below in the depth first fashion
Developed by: Narendran K
RegisterNumber: 212223230135
*/
struct node* createNode(int v) {
    struct node* newNode=malloc(sizeof(struct node));
    newNode->vertex=v;
    newNode->next=NULL;
    return newNode;
}
```
## Output:
![5 c](https://github.com/user-attachments/assets/f71e30e2-447d-4c0c-a022-254be63cc097)

## Result:
Thus, the C code for the function createNode to traverse the graph below in the depth first fashion is implemented successfully
