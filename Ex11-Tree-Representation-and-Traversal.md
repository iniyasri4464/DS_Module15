# Ex11 Tree Representation and Traversal
## DATE: 15/03/2025
## AIM:
To write a C function to perform post order traversal of a binary tree.

## Algorithm
```
1. Start the program.
2. Include required libraries.
3. Create a structure for storing the nodes.
4. Define a function for post order traversal of a binary tree.
5. End the program.
``` 

## Program:
```
/*
Program to perform post order traversal of a binary tree.
Developed by: INIYASRI S
RegisterNumber: 212223230081
*/
#include <stdio.h>
#include <stdlib.h>
struct node {
    
    int data;
    struct node *left;
    struct node *right;
  
};
void postOrder( struct node *root) {
    if(root==NULL)
    return;
    else
    {
        postOrder(root->left);
        postOrder(root->right);
        printf("%d ",root->data);
    }
}
```

## Output:
![image](https://github.com/user-attachments/assets/d67d9a8b-33a4-4284-8bb3-4009010e5b41)



## Result:
Thus, the function to perform post order traversal of a binary tree is implemented successfully
