Memory Management Simulator

A C-based memory management simulator designed for the Advanced Operating Systems course. This project illustrates key concepts of memory management in operating systems, including memory allocation using the First-Fit strategy, deallocation, and compaction to resolve fragmentation. The program uses a linked list to represent memory blocks and provides functions to initialize, allocate, deallocate, compact, and display the memory state.

Features
First-Fit Allocation: Allocates memory by finding the first free block large enough for the requested size.
Deallocation: Frees memory and merges adjacent free blocks to reduce fragmentation.
Compaction: Reorganizes memory to eliminate fragmentation by consolidating free space into a single block.
Memory Visualization: Prints the memory state, showing addresses, sizes, and statuses (free or allocated) of all blocks.
Educational Demo: Includes a step-by-step demonstration in the main function to showcase allocation, fragmentation, and compaction.
