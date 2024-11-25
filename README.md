# Recursion and Divide-and-Conquer Examples in Java

This Java program contains multiple methods demonstrating recursion and the divide-and-conquer algorithmic paradigm. It includes examples of binary search, Fibonacci sequence generation, factorial computation, and indirect recursion.

---

## File

### **binarySearchExample.java**
- **Purpose**: Demonstrates the power of recursion in solving problems such as binary search, factorial computation, Fibonacci sequence generation, and indirect recursion.
- **Features**:
  - Implements a divide-and-conquer approach with binary search.
  - Computes Fibonacci numbers and factorials using recursion.
  - Showcases indirect recursion with two mutually calling methods.

---

## Methods

### **`binarySearch(int[] arr, int target, int left, int right)`**
- **Purpose**: Finds the index of a target element in a sorted array using the binary search algorithm.
- **Parameters**:
  - `arr`: Sorted array of integers.
  - `target`: Element to search for.
  - `left`: Leftmost index of the current search range.
  - `right`: Rightmost index of the current search range.
- **Returns**:
  - Index of the target element if found; `-1` otherwise.
- **Time Complexity**: O(log n).
- **Example**:
  ```java
  int[] arr = {1, 3, 5, 7, 9};
  int index = binarySearch(arr, 5, 0, arr.length - 1);
  System.out.println("Index: " + index); // Output: 2
