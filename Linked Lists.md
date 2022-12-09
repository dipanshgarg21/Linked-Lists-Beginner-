# Linked-Lists-Beginner-
## Limitations of an array:

Arrays require elements be stored in contiguous blocks of memory, which can make it more difficult and time-consuming to insert or delete elements.

Some other disadvantages of arrays include that they have a fixed size, which means that once you create an array, you cannot easily add or remove elements from it without potentially wasting a lot of memory. This can make arrays inflexible and can make it difficult to use them in situations where the size of the data is not known in advance.

---

## What are linked lists?

A **linked list** is a data structure that consists of a group of nodes which together represent a sequence. 

****Advantages of Linked lists:****

![1](https://user-images.githubusercontent.com/95221843/206795251-2a39d608-cda9-463d-bbdf-4f9f656b6e50.png)

Each node contains a piece of data, and a reference to the next node in the sequence. This allows linked lists to be used for efficient insertion and removal of elements, as well as allowing for efficient traversal of the list. Because each node contains a reference to the next node, linked lists can be easily extended or shortened by adding or removing nodes from the list.

The time complexity of insertion as well as deletion in a linked list is O(1), which can be considered one of the best and its properties of being able to be stored in non continuous memory makes it a programmers choice over a normal List or Array.

---

## Visualisation of Linked lists:

In a linked list, there are 4 things to be considered at most which are important in their implementation, a node, its reference, a head and a tail.

**The node** is basically the value or the element that is being stored in the list itself.

**The reference** is a pointer to the address of the next element in the list itself. Although it might seem memory consuming, but it is the most important element as it allows the element to be stored in non continuous manner in the memory.

![2](https://user-images.githubusercontent.com/95221843/206795284-69026653-a358-4773-9d42-891ff229a639.png)

********The head******** is the starting point which points to the first element of the list. The value of the head is null.

************The tail************ is the ending point of the list to which the pointer of the last elements is pointed. Its value is same as that of head i.e., null.
![3](https://user-images.githubusercontent.com/95221843/206795310-0a9dd6c6-cfba-4a7b-9eb9-15d2e84d0013.png)



---

## Types of linked lists:

- ************************************Singly Linked List:************************************ In a linked list, where the list can only be traversed in a single direction, that linked list is known by singly linked list. A singly linked list only consists of one reference which makes its **traversal unidirectional**.

![4](https://user-images.githubusercontent.com/95221843/206795353-1757bce6-3ad4-473b-be8c-fe341635b497.png)


- ****************************************Doubly Linked List:**************************************** In a linked list, where the list can traversed bi directionally is known by Doubly linked list. In this, two pointers or references are provided, one pointing to the next element of the node and the other pointing the previous.

![5](https://user-images.githubusercontent.com/95221843/206795386-ef46aea6-289a-4c31-a58a-87cd46cdf1f0.png)


<aside>
📜 Doubly linked list is an important and one of the most used type of list as it is capable of bi directional traversing.

</aside>

- ******************Circular Linked List:****************** A circular linked list is like a regular one except for the last element of the list pointing to the first. This has the advantage of allowing to go back back to the first element while traversing a list without starting over.

![6](https://user-images.githubusercontent.com/95221843/206795416-268b1697-169b-44ed-960b-8aed63e8767c.png)


---

## Time complexity of operations of a linked list:

![7](https://user-images.githubusercontent.com/95221843/206795445-2d12bcae-b9c1-4de2-940b-6c9ea5e44205.png)


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
