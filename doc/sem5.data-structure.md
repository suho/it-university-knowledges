# Data Structure

- [Arrays, Iteration, Invariants](#arrays-iteration-invariants)
  - [Arrays](#arrays)
  - [Loops and Iteration](#loops-and-iteration)
  - [Invariants](#invariants)
- [Lists, Recursion, Stacks, Queues](#lists-recursion-stacks-queues)
  - [Linked Lists](#linked-lists)
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

![Image 1]

## Searching

## Efficiency and Complexity

## Trees

## Binary Search Trees

## Priority Queues and Heap Trees

## Sorting

## Hash Tables

## Graphs

[Image 1]: ../img/ds.linked-lists.png