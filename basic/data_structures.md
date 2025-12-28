arrays, lists, hash tables, trees, graphs, stacks, queues, heaps

# Arrays

An array is a fundamental data structure in programming that stores a collection of elements, typically of the same data type, in contiguous memory locations. This structure allows multiple related values to be managed under a single variable name, rather than declaring a separate variable for each. 

## Key Concepts
Elements: The individual values stored within the array.
Index (or Key): A number used to access a specific element in the array. In most programming languages (like C, C++, Java, and Python), indexing starts at 0.
Contiguous Memory: Elements are stored next to each other in memory, which allows for efficient, direct access to any element using its index (known as "random access" or O(1) time complexity).
Data Type: In many languages (C, C++, Java), all elements in an array must be of the same data type (e.g., all integers or all strings). Python lists, while similar, can store elements of mixed types.
Fixed Size: In languages like C and C++, the size of an array is typically fixed at the time of declaration and cannot be changed later. Other data structures like dynamic arrays (or ArrayList in Java, list in Python) can grow or shrink dynamically. 

## Common Uses
Arrays are versatile and used in almost every program: 
Storing a list of scores in a game.
Managing a collection of products or users.
Implementing other data structures like stacks, queues, and hash tables.
Representing mathematical matrices or tables (multidimensional arrays).

// TODO: Continue...

## Examples

Typescript:
```ts
// ts
const arr_num: number[] = [0, 1, 2, 3]
```

Go:
```go
// Declare and initialize an array
primes := [6]int{2, 3, 5, 7, 11, 13}
```

Python:
```py
# A list of integers (works like a general array)
numbers_list = [1, 2, 3, 4, 5]
```
