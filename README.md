# Queue:
## Theory:
The queue is a basic data structure just like a stack. In contrast to stack that uses the LIFO approach, queue uses the FIFO (first in, first out) approach.
With this approach, the first item that is added to the queue is the first item to be removed from the queue. Just like Stack, the queue is also a linear data structure.<br>
In software terms, the queue can be viewed as a set or collection of elements as shown below. The elements are arranged linearly.<br>
![queue](https://github.com/Rutuja-117/Queue/assets/139907839/0f57b51f-a9a7-49db-ae1a-e96cf99ba028)
We have two ends i.e. “front” and “rear” of the queue. When the queue is empty, then both the pointers are set to -1.

The “rear” end pointer is the place from where the elements are inserted in the queue. The operation of adding /inserting elements in the queue is called “enqueue”.

The “front” end pointer is the place from where the elements are removed from the queue. The operation to remove/delete elements from the queue is called “dequeue”.

When the rear pointer value is size-1, then we say that the queue is full. When the front is null, then the queue is empty.

#### Basic operations:
The queue data structure includes the following operations:<br>

EnQueue: Adds an item to the queue. Addition of an item to the queue is always done at the rear of the queue.<br>
DeQueue: Removes an item from the queue. An item is removed or de-queued always from the front of the queue.<br>
isEmpty: Checks if the queue is empty.<br>
isFull: Checks if the queue is full.<br>
peek: Gets an element at the front of the queue without removing it.<br>
