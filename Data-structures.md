# Introduction to Data Structures
A data structure is a way to store and organize data in a computer so that it can be used efficiently.<br>
**Efficieny**: Efficiency of data structures is always measured in terms of time and space.<br>
In other words, it is used to implement an ADT.<br>
For example, in order to implement stack ADT, we can use an arry data structure or linked list data structure.<br>
ADT tells us what is to be done and data structures tells us how to do it.

## Types of Data Structure
1. **Linear Data Structures**: A data structure is linear when all the elements are arranged in a linear (sequential) order.<br>
Examples: Array, Queue, Stack, and Linked List.
2. **Non Linear Data Structures**: A data structure is non linear when all the elements are not arranged in a linear (sequential) order.<br>
Examples: Tree, Graph

## What is static Data structures?
In these type of data structures, the memory is allocated at compile time. Therefore, maximum size is fixed.<br>
Advantage: Fast access<br>
Disadvantage: Slower insertion and deletion<br>
Example: Array

## What is Dynamic Data structures?
In these type of data structures, the memory is allocated at the run time. Therefore, maximum size is flexible.<br>
Advantages: Faster insertion and deletion<br>
Disadvantages: Slower access<br>
Example: Linked list

## What is a data type?
Two important things about data types:
1. Defines a certain domain of values.
2. Defines Operations allowed on those values.

Example:
int type
* Takes only integer values
* Operations: addition, subtraction, multiplication, bitwise operations etc.

## What is a User defined data type?
The operations and values of the user defined data types are not specified in the language itself but specified by the user.<br>
Example: "Structure", "Union", and "Enumeration".

By using structures, we are defining our own type by combining other data types.

# Abstract data type
ADTs are like user defined data types which defines operations on values using functions without specifying what is there inside the function and how the operations are performed.

Example: Stack ADT<br>
A stack consists of elements of same type arranged in a sequential order.
Operations:
* initialize() - initializing it to be empty.
* push() - insert an element into the stack.
* pop() - delete an element from the stack.
* isEmpty() - check if stack is empty.
* ifFull() - check if the stack is full.

## Which data structure?
In reality, different implementations of ADT are compared for time and space efficiency. The one best suited according to the current requirement of the user will be seleted.

## Advantages of data structures
* Efficiency - proper choice of data strutures make a program efficient in terms of space and time.
* Reusability - one implementation can be used by multiple client.
* Abstraction - Data structures is specified by an ADT which provides a level of abstraction. The client program doesn't have to worry about the implementation details.
