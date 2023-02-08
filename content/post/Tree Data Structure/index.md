---
title: Tree Data Stucture
description: What is Tree, and their different types?
slug: (○'◡'○)
date: 2023-02-08 00:00:00+0000
image: cover.jpg
categories:
    - Data Structure & Algorithms
tags:
    - Binary Tree
---

## What is Tree?
A tree is a nonlinear hierarchical data structure that consists of nodes connected by edges.

## Why using Tree?
It is a non-linear data structure.

Other data structures such as arrays, linked list, stack, and queue are linear data structures that store data sequentially. 

In order to perform any operation in a linear data structure, **the time complexity increases with the increase in the data size.**

## Tree Terminologies

### Node
A node is an entity that **contains a key or value and pointers** to its child nodes.

The last nodes of each path are called *leaf nodes* or *external nodes* that do not contain a link/pointer to child nodes.

The node having at least a child node is called an *internal node*.

### Edge
It is the *link* between any two nodes.

### Root
It is the topmost node of a tree.

### Depth & Height

The *depth* of a node is the number of edges from the root to the node.

The *height* of a Tree is the height of the root node or the depth of the deepest node.

> Height and Depth of each node in a tree:
![Height and depth](https://cdn.programiz.com/sites/tutorial2program/files/height-depth_1.png)

### Degree of a Node
The *degree* of a node is the **total number of branches** of that node.

### Forest
A collection of disjoint trees is called a *forest*.

> Creating forest from a tree:
![Disjoint tree](https://cdn.programiz.com/sites/tutorial2program/files/forest_0.png)

## Types of Tree

1. Binary Tree
2. Binary Search Tree
3. AVL Tree
4. B-Tree

## Tree Traversal
-[link](https://www.programiz.com/dsa/tree-traversal)

## Tree Aplication
- *Binary Search Trees*(BSTs) are used to quickly check whether an element is **present in a set or not**.
- *Heap* is a kind of tree that is used for heap sort.
- A modified version of a tree called Tries is used in modern routers to store routing information.
- Most popular databases use *B-Trees* and *T-Trees*, which are variants of the tree structure we learned above to store their data
- Compilers use a syntax tree to validate the syntax of every program you write.