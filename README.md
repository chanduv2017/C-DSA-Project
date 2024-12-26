
# Sorting Algorithms Implementation

## Overview
This project was developed as part of the CSE107 course. It is a menu-driven program written in C that demonstrates the implementation of various sorting algorithms. Users can input an array of integers and select a sorting technique to sort the array. The program also measures and displays the execution time for each sorting algorithm.

---

## Features
- Implements the following sorting algorithms:
  - **Insertion Sort**
  - **Bubble Sort**
  - **Selection Sort**
  - **Quick Sort**
  - **Merge Sort**
- Allows the user to choose a sorting algorithm through a menu.
- Calculates and displays the time taken by the selected sorting algorithm to execute.
- Provides the sorted array as output.

---

## Sorting Algorithms Explained

### 1. **Insertion Sort**
- A simple sorting algorithm that builds the final sorted array one item at a time.
- Time Complexity: O(n^2) in the worst case.

### 2. **Bubble Sort**
- A simple comparison-based algorithm where larger elements "bubble up" to the end of the array.
- Time Complexity: O(n^2) in the worst case.

### 3. **Selection Sort**
- Repeatedly finds the minimum element from the unsorted portion and moves it to the sorted portion.
- Time Complexity: O(n^2) in all cases.

### 4. **Quick Sort**
- A divide-and-conquer algorithm that selects a pivot and partitions the array around it.
- Time Complexity: O(n log n) on average, O(n^2) in the worst case.

### 5. **Merge Sort**
- A divide-and-conquer algorithm that splits the array into halves, sorts each half, and then merges them.
- Time Complexity: O(n log n) in all cases.

---

## How to Use
1. Compile the program using a C compiler:
   ```bash
   gcc sorting_algorithms.c -o sorting_algorithms
   ```
2. Run the program:
   ```bash
   ./sorting_algorithms
   ```
3. Follow the on-screen instructions:
   - Enter the size of the array.
   - Input the elements of the array.
   - Choose a sorting algorithm from the menu.
   - View the sorted array and execution time.
   - Optionally, run the program again with a different array or sorting method.

---

## Example Output
```
**********************************************************************************************************************************************
                                     Menu-Driven Program to Implement Different Sorting Algorithms
**********************************************************************************************************************************************

Enter the size of the array: 5
Enter the elements of the array:
10 5 3 8 6
Elements in array are: 10 5 3 8 6 
Which method to follow: 
 1) Insertionsort 
 2) Bubblesort 
 3) Selectionsort 
 4) Quicksort
 5) Mergesort

Enter Your Choice: 4
Quicksort took 0.000002 seconds to execute.
Sorted array is: 3 5 6 8 10 
Do you want to run again (0 or 1)? 0
Program ended!
```

---

## File Structure
- **sorting_algorithms.c**: The main source code implementing the sorting algorithms and menu-driven interface.
- **README.md**: Documentation for the project.

---

## Requirements
- A C compiler (e.g., GCC).

---
