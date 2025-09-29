AIM:-
To study and implement Queue data structure using array in C++ with menu options:
i) Insert (Enqueue)
ii) Delete (Dequeue)
iii) Display
iv) Exit

Theory
A Queue is a linear data structure that follows the FIFO (First In, First Out) principle. This means that the element inserted first will be removed first, just like people standing in a line.

A queue has two primary operations:
Enqueue (Insert): Adds an element to the rear of the queue.
Dequeue (Delete): Removes an element from the front of the queue.
Other operations include Display, which shows all elements from front to rear.

Queue Representation Using Array
A queue can be implemented using an array of fixed size.

Two pointers are maintained:
Front: Points to the first element.
Rear: Points to the last inserted element.

Initially, both are set to -1 (indicating an empty queue).
On insertion, rear increases.
On deletion, front increases.

Conditions
Queue Overflow: If rear == SIZE - 1, no new element can be inserted.
Queue Underflow: If front == -1 or front > rear, queue becomes empty.

Applications of Queue
Job scheduling in operating systems.
Handling requests in web servers.
Data buffering in communication systems.
Printer and resource management.

ALGORITHM:-
nitialize front = -1 and rear = -1.
Enqueue (Insert):
Check for overflow (rear == SIZE - 1).
If queue empty, set front = 0.
Increment rear and insert value.

dequeue (Delete):
Check for underflow (front == -1 or front > rear).
Print and remove the element at front.
Increment front.

Display:
If empty, print "Queue is empty".
Else, print elements from front to rear.

Exit: End the program.

CONCLUSION:-
A Queue was successfully implemented using arrays.
Operations performed were:
Enqueue (Insert) → Adding elements at the rear.
Dequeue (Delete) → Removing elements from the front.
Display → Showing all current elements in the queue.
The concepts of overflow and underflow conditions were also demonstrated.
Thus, the Queue data structure using array has been successfully studied and implemented.
