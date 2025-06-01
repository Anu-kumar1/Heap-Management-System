## Heap Management System (Buddy System)

This C program simulates a **heap memory management system** using the **Buddy System** algorithm. Memory blocks are managed in sizes that are powers of two, allowing efficient allocation and deallocation with minimal fragmentation.

### Features

* **Memory size**: 1024 bytes
* **Minimum block size**: 16 bytes
* **Dynamic allocation** using power-of-two block splitting
* **Efficient deallocation** with automatic block merging (buddy coalescing)
* **Interactive menu** to:

  * Allocate memory
  * Free memory
  * View free memory blocks
  * View allocated memory blocks

### How It Works

* Memory is represented as a static array.
* Free blocks are stored in a set of free lists (based on block size).
* Allocation finds the smallest suitable block and splits larger blocks if necessary.
* Deallocation merges free blocks with their buddies if possible.


