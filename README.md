# Queues In C

In C, a queue is essentially a linear data structure for managing and storing data components. It adheres to the First In First Out (FIFO) principle.

The first element added to an array in a queue is also the first element withdrawn from the array.

Let's use the example of a ticket booth for buses as an example. Here, a C programming queue style is utilised. The first person to arrive will be issued with the tickets, as they are given out on a first-come, first-served basis.

There is an open queue at both ends. There are two ends: one for inserting data and the other for removing it.

## Operations Associated with a Queue in C

#### A queue being an Abstract Data Structure provides the following operations for manipulation on the data elements:

isEmpty(): To check if the queue is empty

isFull(): To check whether the queue is full or not

dequeue(): Removes the element from the frontal side of the queue

enqueue(): It inserts elements to the end of the queue

Front: Pointer element responsible for fetching the first element from the queue

Rear: Pointer element responsible for fetching the last element from the queue

![queues](https://user-images.githubusercontent.com/124857399/234080225-021bd7ab-7fb8-4860-a8ad-864990fa5677.png)


## Working of Queue Data Structure


Queue follows the First-In-First-Out pattern. The first element is the first to be pulled out from the list of elements.

The first and last elements in the queue are tracked by the front and rear pointers.
The queue must first be initialised by setting Front = -1 and Rear = -1.
We must determine whether the queue is already full before inserting the element (enqueue), i.e., determining whether Overflow is present. We must move the element to the Rear pointer variable's position and increase the value of the Rear index by 1 if the queue is not full. We must set the value of Front to 0 before adding the first piece to the queue.
The condition for Underflow must be met in order to dequeue the element from the queue and determine whether the queue is already empty. The element at the Front pointer location must be removed, returned, and the Front index value must then be increased by 1 if the queue is not empty. We must set the Front and Rear index values to -1 in order to delete the last member from the queue.

#### NOTE:- A queue can be implemented using Stacks by either of the following ways:

Making the enqueue operation costly
Making the dequeue operation costly


### Applications of Queue Data Structure

CPU Scheduling
Disk Scheduling
Asynchronous data transfer between processors such as File IO, etc.
Breadth-First Search Algorithm (BFS)



