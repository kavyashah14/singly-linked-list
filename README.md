# Singly linked list
Singly Linked List in C is one of the simplest linear data structures, that we use for storing our data in an easy and efficient way.  Linked List in C comprises nodes like structures, which can further be divided into 2 parts in the case of a singly linked list. 

These two parts are-:

Node – for storing the data.
Pointer – for storing the address of the next node.
In a Singly linked list there is only one pointer type variable, that contains the address of the next node.

![image](https://user-images.githubusercontent.com/70435939/234358957-803a1810-903f-4583-9250-8c4df4f3c63a.png)

The syntax for creating a node

struct Node

{

  int Data;
  
  Struct Node *next;
  
};

# Applications of Singly Linked List :

The singly linked list is used to implement stack and queue.
The undo or redo options, the back buttons, etc., that we discussed above are implemented using a singly linked list.
During the implementation of a hash function, there arises a problem of collision, to deal with this problem, a singly linked list is used.
