Multi-Sorting Algorithm Implementation in Python
This repository contains a Python script that implements three different sorting algorithms: QuickSort, MergeSort, and HeapSort. The script also includes functions for merging two and three arrays.

Sorting Algorithms
QuickSort: A divide-and-conquer algorithm. It works by selecting a ‘pivot’ element from the array and partitioning the other elements into two sub-arrays, according to whether they are less than or greater than the pivot.

MergeSort: Also a divide-and-conquer algorithm. It works by dividing the unsorted list into n sublists, each containing one element (a list of one element is considered sorted), and repeatedly merging sublists to produce new sorted sublists until there is only one sublist remaining.

HeapSort: This is a comparison-based sorting algorithm. It divides its input into a sorted and an unsorted region, and it iteratively shrinks the unsorted region by extracting the largest element and moving that to the sorted region.

Merging Functions
The script also includes functions to merge two and three arrays. These functions take sorted arrays as input and return a single array that contains all elements from the input arrays in sorted order.

Usage
The script sorts an array using each of the three sorting algorithms, and then merges the sorted arrays. The time taken by each sorting algorithm and the total execution time of the script are printed to the console.

