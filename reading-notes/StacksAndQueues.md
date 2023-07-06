# Stacks and Queues

#### A stack is a data structure that follows either the FILO (First In Last Out) or LIFO (Last In First Out) principle. It is composed of nodes where each node points to the next node in the stack but not the previous node. The main operations on a stack include:

>Push: Adds a new node to the top of the stack. This operation has a constant time complexity of O(1) regardless of the stack's size.

>Pop: Removes the top node from the stack and returns its value. This operation also has a constant time complexity of O(1).

>Peek: Retrieves the value of the top node without removing it from the stack. This operation has a constant time complexity of O(1).

>IsEmpty: Checks if the stack is empty and returns true if it is, otherwise false. This operation also has a constant time complexity of O(1).

#### On the other hand, a queue is a data structure that follows the FIFO (First In First Out) or LILO (Last In Last Out) principle. It consists of nodes where new nodes are added at the rear and removed from the front. The key operations on a queue are:

>Enqueue: Inserts a new node at the rear of the queue. Similar to stack operations, enqueue has a constant time complexity of O(1).

>Dequeue: Removes the front node from the queue and returns its value. Dequeue operation also has a constant time complexity of O(1).

>Peek: Retrieves the value of the front node without removing it from the queue. This operation has a constant time complexity of O(1).

>IsEmpty: Checks if the queue is empty and returns true if it is, otherwise false. Like other operations, isEmpty also has a constant time complexity of O(1).

