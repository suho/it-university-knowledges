# Data Structure

- [Arrays, Iteration, Invariants](#arrays-iteration-invariants)
  - [Arrays](#arrays)
  - [Loops and Iteration](#loops-and-iteration)
  - [Invariants](#invariants)
- [Lists, Recursion, Stacks, Queues](#lists-recursion-stacks-queues)
  - [Linked Lists](#linked-lists)
  - [Recursion](#recursion)
  - [Stacks](#stacks)
  - [Queues](#queues)
  - [Graphical Representation](#graphical-representation)
- [Searching](#searching)
- [Efficiency and Complexity](#efficiency-and-complexity)
- [Trees](#trees)
- [Binary Search Trees](#binary-search-trees)
- [Priority Queues and Heap Trees](#priority-queues-and-heap-trees)
- [Sorting](#sorting)
- [Hash Tables](#hash-tables)
- [Graphs](#graphs)

## Arrays, Iteration, Invariants

### Arrays

In CS, the obvious way to store an ordered collection of items is as an **array**. Array items are typically stored in a sequence of computer memory locations.

### Loops and Iteration

The standard approach in most programming languages for repeating a process a certain number of times, such as moving sequenctially through an array to perform the same operations on each item, involves a **loop**.

```java
for (i=0; i<N; i++) {
    // do something
}
```

There is **iteration** over the index **i**.

### Invariants

An invariants, as the name suggests, is a condition that does not change during execution of a given program or algorithm.

For example:

- Simple inequality: `i < 20`
- Something more abstract: `the items in the array are sorted`

Invariants are important for data structures and algorithms because they enable **correctness proofs** and **verification**

## Lists, Recursion, Stacks, Queues

### Linked Lists

#### Graphical Reresentation

Non-empty **lists** can be represented by **two cells**, in each of which the first cell contains a _pointer_ to a list **element** and the second cell contains a _pointer_ to either the empty list or another two-cell.

For instance, the list `[3, 1, 4, 2, 5]`

![Image 1]

#### Working with Lists

- Constructed
- Access element of Lists
- Check empty
- Replace element

### Recursion

For-loops was a natural way to process collections of items stored in arrays. When items are stored as linked-lists, there is no index for each item, and recursion provides the natural way to process.

### Stacks

**Stack** are, on an abstract level, equivalent to linked lists. They are the ideal data structure to model a First-In-Last-Out (FILO), or Last-In-First-Out (LIFO), strategy in search.

#### Graphical Representation

Their relation to linked lists means that their graphical representation can be the same, but different in the orider of the items.

For instance, stack `[3, 1, 4, 2, 5]`

![Image 2]

#### Working with Stack

- Constructed
- Push
- Get Top
- Pop
- Check Empty

### Queues

A **queue** is a data structure used to model a First-In-First-Out (FIFO) strategy. Conceptually, we add to the end of a queue and take away elements from its front

### Graphical Representation

A queue can be graphically represented in a similar way to a list or stack, but with an additional two-cell in which the first element points to the front of the list of all the elements in the queue, and the second element points to the last element of the list.

For instance, queue `[3, 1, 4, 2]`

![Image 3]

## Searching

## Efficiency and Complexity

## Trees

## Binary Search Trees

## Priority Queues and Heap Trees

## Sorting

## Hash Tables

## Graphs

[Image 1]: ../img/ds.linked-lists.png
[Image 2]: ../img/ds.stacks.png
[Image 3]: ../img/ds.queues.png