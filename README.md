# Linked List Functions
![Screenshot 2023-03-21 151700](![image](https://github.com/Madmohammed22/Linked-list/assets/121677014/28bbad18-bc52-4818-a3bb-8d3029350529)
)

This repository contains a collection of functions for working with singly-linked lists in C. These functions are implemented in the `ft_list.h` header file and are designed to provide various operations on linked lists, including insertion, traversal, manipulation, and search. Below is an overview of the linked list and some of the useful functions available in this library.

## Linked List Overview

A singly-linked list is a fundamental data structure that consists of nodes, each containing a value and a pointer to the next node. Linked lists are versatile and can be used for various purposes, such as maintaining a collection of data, implementing dynamic data structures, and more. This library offers a set of functions to work with singly-linked lists.

## Available Functions

### 1. `void ft_add(void *data)`

This function adds a new node with the specified data to the end of the linked list.

### 2. `void ft_push(struct ListNode **begin_list, int number)`

This function pushes a new node with the given number to the front of the linked list.

### 3. `void ft_print_list(struct ListNode *node)`

Prints the elements of the linked list starting from the provided node.

### 4. `struct ListNode *middleNode(struct ListNode *head)`

Finds and returns the middle node of the linked list.

### 5. `void ft_list_foreach(struct ListNode *begin_list, void (*f)(void *))`

Applies the function `f` to each element in the linked list.

### 6. `void ft_list_foreach_if(struct ListNode *begin_list, void (*f)(void *), void *data_ref, int (*cmp)())`

Applies the function `f` to elements in the linked list that match the criteria defined by `cmp`.

### 7. `int cmp(const void *a, const void *b)`

A comparison function used for searching and comparison operations.

### 8. `bool cmp1(const void *a, const void *b)`

A specialized comparison function for specific use cases.

### 9. `int search(void *arr, int n, int size_int, void *x, bool(cmp1)(const void *, const void *))`

Searches for an element `x` in an array `arr` of size `n` using the comparison function `cmp1`.

### 10. `int ft_list_size(struct ListNode *head)`

Returns the size (number of elements) of the linked list.


For detailed usage instructions and examples, please refer to the source code and comments in the `ft_list.h` file.

Feel free to use and contribute to this repository for enhancing your linked list operations in C.
