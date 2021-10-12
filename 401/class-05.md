
# Class 05

[Home](https://markjackson28.github.io/reading-notes/)

## Summary/Notes of readings

*[Big O: Analysis of Algorithm Efficiency](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/big_oh.html)*

- ‘Big O(oh) notation is used to describe the efficiency of an algorithm or function. This efficiency is evaluated based on 2 factors:

> Running Time (also known as time efficiency / complexity)The amount of time a function needs to complete.

> Memory Space (also known as space efficiency / complexity)The amount of memory resources a function uses to store data and instructions.’

- ‘Big O’s role in algorithm efficiency is to describe the Worst Case of efficiency an algorithm can have in performing it’s job.’

*[Linked Lists](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/singly_linked_list.html)*

*Terminology*

- Linked List - A data structure that contains nodes that links/points to the next node in the list.
- Singly - Singly refers to the number of references the node has. A Singly linked list means that there is only one reference, and the reference points to the Next node in a linked list.
- Doubly - Doubly refers to there being two (double) references within the node. A Doubly linked list means that there is a reference to both the Next and Previous node.
- Node - Nodes are the individual items/links that live in a linked list. Each node contains the data for each link.
- Next - Each node contains a property called Next. This property contains the reference to the next node.
- Head - The Head is a reference of type Node to the first node in a linked list.
- Current - The Current is a reference of type Node to the node that is currently being looked at. When traversing, you create a new Current variable at the Head to guarantee you are starting from the beginning of the linked list.

*[What’s a Linked List, Anyway pt1](https://medium.com/basecs/whats-a-linked-list-anyway-part-1-d8b7e6508b9d)*

- 'The fundamental difference between arrays and linked lists is that arrays are static data structures, while linked lists are dynamic data structures.'
- Types of linked list: singly, doubly, circular.

*[What’s a Linked List, Anyway pt2](https://medium.com/basecs/whats-a-linked-list-anyway-part-2-131d96f71996)*

- O(1): constant
- O($n$): linear
- O($n^{2}$): exponential
