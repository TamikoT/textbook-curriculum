# Stacks and Queues
## Goals
+ Introduction to Stacks
+ Memory address space and call stacks/activation records
+ Introduction to Queues
+ Circular buffer


## Offline Reading Material
Go through what you've already learned:
+ Revise classroom session on [Stacks and Queues](https://github.com/Ada-Developers-Academy/textbook-curriculum/blob/master/04-cs-fundamentals/classroom/02-ADTs-Stacks-Queues.md)

Find the reading material that helps you learn from the below links:
+ Kal academy's material on [Stacks and Queues](https://drive.google.com/open?id=0BxHords9odw3a2V5cVpkNTl2amc)
+ Read about [Method Call Stack](https://drive.google.com/open?id=0BxHords9odw3cG9WM1Y2S0FQWVE)
+ Read about [Stacks](https://simple.wikipedia.org/wiki/Stack_(data_structure)) on Wikipedia
+ Read about [Queues](https://en.wikipedia.org/wiki/Queue_(abstract_data_type)) on Wikipedia
+ CMU lecture notes on [Stacks and Queues](https://www.cs.cmu.edu/~adamchik/15-121/lectures/Stacks%20and%20Queues/Stacks%20and%20Queues.html)

## Offline Problem Sets
+ Implement a Stack using an array to hold integer data
+ Implement a Stack using a linked list to hold integer data
+ Implement a Queue using an array to hold integer data
+ Implement a Queue using a linked list to hold integer data

Add the following functions to each of the above:
+ Empty() which returns true is the data structure is empty, false otherwise
+ Size() which returns the number of items in the data structure
+ Front() which returns the item that would be dequeued next (for Queue) 
+ Top() which returns the item that would be popped next (for Stack)
+ Min() which returns the minimum integer data value in the data structure
+ Max() which returns the maximum integer data value in the data structure

Challenge Problems:
+ Write a function to print all integer values in a binary tree in breadth first traversal iteratively. (Hint: Use a Queue.)
+ How would you implement a Queue using 2 Stacks?
+ How would you implement a Stack using 2 Queues?

Additional problems:
+ In "Cracking the Coding Interview" book, "Chapter 3: Stacks and Queue"
+ Kal academy's problems on [Stacks and Queues](https://drive.google.com/open?id=0BxHords9odw3b2d1ZTJtVkZZTkk)

## In Class
Here's the problems we'll cover in class.
Design and implement pseudo code for:
+ 1. Implement Top for a Stack using only Push(e) and Pop. (Note: This is an example of extending functionality without knowing the implementation details of how the Stack is implemented i.e. not knowing whether the Stack is implemented using an array or a linked list). Assume the data contained is int.
+ 2. Implement Front for a Queue using only Dequeue, Enqueue(e) & Empty.  (Note: This is an example of extending functionality without knowing the implementation details of how the Queue is implemented i.e. not knowing whether the Queue is implemented using an array or a linked list) Assume the data contained is int. Feel free to use additional data structures.
+ 3. Write a function to reverse a string (the funciton takes a string as input parameter) using a Stack.
+ 4. Write a function to print all integer values in a binary tree in pre-order traversal iteratively. (Hint: Use a Stack.)
</br>

## Slide deck
+ Slide deck used in class</br>
<span xmlns:dct="http://purl.org/dc/terms/" property="dct:title"><a href="https://www.slideshare.net/secret/mYt7lab98fGApm">Stacks and Queues</a></span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>.</br>
<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br />
