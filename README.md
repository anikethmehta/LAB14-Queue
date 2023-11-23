### ***Date*** : 2 November 2023
### ***Title*** : LAB14-Queue
### ***Aim*** : Queue Implementation
### ***Algorithm*** : 

Enqueue (Add an element to the queue):
If the queue is not full, we can add an element to it.
If the queue is empty, set both the front and rear pointers to the first position.
Otherwise, move the rear pointer to the next position and store the new element there.

Dequeue (Remove an element from the queue):
If the queue is not empty, we can remove an element from it.
If the queue has only one element, set both the front and rear pointers to -1 (indicating an empty queue).
Otherwise, move the front pointer to the next position.

Display (Show all elements in the queue):
If the queue is not empty, we can display its elements.
Start from the front and move towards the rear, showing each element one by one.

Peek (Get the front element without removing it):
If the queue is not empty, we can see the element at the front without removing it.
Simply display the element at the front position.

These operations ensure that elements are added at the rear and removed from the front, maintaining the first-in-first-out (FIFO) order.

### ***Explanation*** :

Enqueue (Add an element to the queue):
Think of the queue like a line of people waiting for something.
Enqueue is like adding a person to the back of the line.
If the line is empty, the person becomes the first in line. If not, they join the line behind the last person.

Dequeue (Remove an element from the queue):
Dequeue is like when the first person in the line gets what they were waiting for and leaves.
If there's only one person in line, the line becomes empty. Otherwise, the second person becomes the first.

Display (Show all elements in the queue):
Display is like looking at the entire line of people.
Starting from the first person, you look at each one until you reach the last.

Peek (Get the front element without removing it):
Peek is like checking who is the first person in line without asking them to leave.
You just take a quick look at the front without changing anything.

### ***Output Screenshot*** :

Code:

Output:
