# Linked-Lists-Beginner-
## Limitations of an array:

Arrays require elements be stored in contiguous blocks of memory, which can make it more difficult and time-consuming to insert or delete elements.

Some other disadvantages of arrays include that they have a fixed size, which means that once you create an array, you cannot easily add or remove elements from it without potentially wasting a lot of memory. This can make arrays inflexible and can make it difficult to use them in situations where the size of the data is not known in advance.

---

## What are linked lists?

A **linked list** is a data structure that consists of a group of nodes which together represent a sequence. 

****Advantages of Linked lists:****

!(https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c044d1e2-e27e-40e8-a486-e618a1c1fc25/Untitled.png)

Each node contains a piece of data, and a reference to the next node in the sequence. This allows linked lists to be used for efficient insertion and removal of elements, as well as allowing for efficient traversal of the list. Because each node contains a reference to the next node, linked lists can be easily extended or shortened by adding or removing nodes from the list.

The time complexity of insertion as well as deletion in a linked list is O(1), which can be considered one of the best and its properties of being able to be stored in non continuous memory makes it a programmers choice over a normal List or Array.

---

## Visualisation of Linked lists:

In a linked list, there are 4 things to be considered at most which are important in their implementation, a node, its reference, a head and a tail.

**The node** is basically the value or the element that is being stored in the list itself.

**The reference** is a pointer to the address of the next element in the list itself. Although it might seem memory consuming, but it is the most important element as it allows the element to be stored in non continuous manner in the memory.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6c5e8349-47c6-4a85-aa79-48b1b26d5371/Untitled.png)

********The head******** is the starting point which points to the first element of the list. The value of the head is null.

************The tail************ is the ending point of the list to which the pointer of the last elements is pointed. Its value is same as that of head i.e., null.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f414fa60-29c8-412c-92f3-bc63c69116a6/Untitled.png)

---

## Types of linked lists:

- ************************************Singly Linked List:************************************ In a linked list, where the list can only be traversed in a single direction, that linked list is known by singly linked list. A singly linked list only consists of one reference which makes its **traversal unidirectional**.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d6fa046b-b2c6-4bf2-9b69-f427b6adafc0/Untitled.png)

- ****************************************Doubly Linked List:**************************************** In a linked list, where the list can traversed bi directionally is known by Doubly linked list. In this, two pointers or references are provided, one pointing to the next element of the node and the other pointing the previous.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/974e0f4f-5efe-4728-be9d-306593fb4da7/Untitled.png)

<aside>
📜 Doubly linked list is an important and one of the most used type of list as it is capable of bi directional traversing.

</aside>

- ******************Circular Linked List:****************** A circular linked list is like a regular one except for the last element of the list pointing to the first. This has the advantage of allowing to go back back to the first element while traversing a list without starting over.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b2778a60-0a9f-40cf-9d60-006f2834fc3a/Untitled.png)

---

## Time complexity of operations of a linked list:

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/15ad27b2-e13f-4865-b341-3bf738cd4f1d/Untitled.png)

As shown in the above figure, it can be concluded that the search and accessing operations are costly in a linked list. It is because, in order to traverse the whole list, it is required to start from the very first element, from which we move on to the second element using its corresponding reference. This step is repeated in multiple orders till the element pointed by the reference is not tail.

Hence, a linked list does not have direct access to its elements which states it as its major limitation, unlike lists/arrays.

---

## Applications of Linked lists

A linked list has many applications:

1. It is used in the implementation of Instagram reels, a music playlist etc.
2. It is used to create data structures such as stacks and queues.
3. It is used in open chaining of hash maps.
4. In programs, the undo and redo functions are based on the concept of Linked lists.

---

---
