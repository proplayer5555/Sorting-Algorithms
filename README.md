# Sorting-Algorithms

# Sorting Algorithms in C/C++

This repository contains implementations of various sorting algorithms in C/C++, including popular algorithms such as Bubble Sort, Selection Sort, Insertion Sort, Merge Sort, Quick Sort, and Heap Sort.

## Table of Contents

- [Introduction](#introduction)
- [Algorithms Implemented](#algorithms-implemented)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Sorting algorithms are essential in computer science and programming for arranging elements in a specific order. This repository provides implementations of common sorting algorithms in C/C++, enabling developers to understand, experiment with, and utilize these algorithms in their projects.

## Algorithms Implemented

### 1. Bubble Sort

Bubble Sort is a simple comparison-based sorting algorithm that repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. The pass through the list is repeated until the list is sorted.

### 2. Selection Sort

Selection Sort is another simple comparison-based sorting algorithm that divides the input list into two parts: a sorted sublist and an unsorted sublist. It repeatedly selects the smallest (or largest) element from the unsorted sublist and moves it to the end of the sorted sublist.

### 3. Insertion Sort

Insertion Sort builds the final sorted array one item at a time by iteratively inserting each element into its correct position in the sorted portion of the array. It is efficient for small datasets or nearly sorted arrays.

### 4. Merge Sort

Merge Sort is a divide-and-conquer algorithm that divides the input array into two halves, recursively sorts each half, and then merges the sorted halves to produce a single sorted array. It has a time complexity of O(n log n) and is stable and efficient for large datasets.

### 5. Quick Sort

Quick Sort is another divide-and-conquer algorithm that partitions the input array into two subarrays around a pivot element, recursively sorts each subarray, and then combines them to form the final sorted array. It has a time complexity of O(n log n) on average and is widely used due to its efficiency and simplicity.

### 6. Heap Sort

Heap Sort is a comparison-based sorting algorithm that builds a binary heap from the input array and repeatedly extracts the maximum (for max heap) or minimum (for min heap) element from the heap and rebuilds the heap until the array is sorted. It has a time complexity of O(n log n) and is not stable but is efficient for large datasets.

## Usage

To use the sorting algorithms implemented in this repository, follow these steps:

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/proplayer5555/Sorting-Algorithms.git
    ```

2. Compile the C/C++ files using a compatible compiler:

    ```bash
    g++ bubble_sort.cpp -o bubble_sort
    ```

3. Run the compiled executable:

    ```bash
    ./bubble_sort
    ```

4. Follow the prompts or customize the input parameters as needed for your specific problem.

## Contributing

Contributions to this repository are welcome! If you have suggestions for improvements, bug fixes, or new sorting algorithms to add, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
