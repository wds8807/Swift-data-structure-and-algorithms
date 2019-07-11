# Swift-data-structure-and-algorithms
Here let's find some of the most popular algorithms and data structures in Swift, I'll try to explain how they work. Also, I find it important to write down and keep what I have learned so they will stay organized whenever I need to look up. 

## 1. Big O Notation
According to Wiki, big O notation is a mathematical notation that describes the limiting behavior of a function when the argument tends towards a particular value or infinity. Ohh...
Ok, it's just a way to describe the time and space complexity of a function or an algorithm you wrote, i.e., how the function will behave when input is very large. For example, if you want to sort an array of numbers, bubble sort will result in O(n^2) time complexity and merge sort will give you O(n* logn) time complexity, which is much better. Another example is insert or remove a node in a Binary Search Tree, which is O(log*n), very nice, right? But when the tree becomes more and more unbalanced, it will deteteriate to O(n), just like a linked list. More about trees later.

## 2. ```Array``` and ```Dictionary```
```Array``` and ```Dictionary``` are two built in data structures that are extremely optimized and we can implement a ton of other data structures depending on those. In my experience, ```array``` operations are very fast even when time complexity is not constant.

## 3. Stack
First in, last out. We can easily implement a stack using an ```array```. 

## 4. Queue
First in, first out. Just like lining up for boarding the bus. We can also easily implement a queue using an ```array```. Also, using two stacks can give us a queue with constant time complexity for both ```enqueue()``` and ```dequeue()``` operations.

## 5. Linked list
A sequence of data items connected through links. Most important difference from array is that linked list does not support constant time item access, for the reason that it does not conform to protocol ```RandomAccessCollection```.

## 6. Tree
A general purpose tree: each node could have zero, one or more children.
