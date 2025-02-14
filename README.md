# Comparison-based Sorting Algorithms

This project implements and compares the performance of various comparison-based sorting algorithms. The goal is to analyze their execution time for different input sizes and specific cases (sorted and reversely sorted inputs).

## Table of Contents

- [https://github.com/Khondoker-M/Algorithm-Project-/blob/main/Project1.ipynb](#algorithms-implemented)
- [Execution Instructions](#execution-instructions)
- [Performance Analysis](#performance-analysis)
- [Special Cases](#special-cases)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Algorithms Implemented

The following sorting algorithms are implemented in this project:

1. **Insertion Sort**
2. **Merge Sort**
3. **Heapsort** (vector-based, inserting one item at a time)
4. **In-place Quicksort** (pivot: first, last, or random item)
5. **Modified Quicksort**
   - Uses median-of-three as the pivot.
   - For small sub-problems (size ≤ `k`), insertion sort is used.

---

## Execution Instructions

Follow these steps to run the sorting algorithms and analyze their performance:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/comparison-sorting-algorithms.git
   cd comparison-sorting-algorithms
