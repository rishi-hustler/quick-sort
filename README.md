# Quick Sort (Java)

## 📌 Overview

**Quick Sort** is a highly efficient **divide-and-conquer sorting algorithm** that selects a **pivot element**, partitions the array around the pivot, and recursively sorts the subarrays.

It is widely used due to its **in-place sorting** and average-case performance.

---

## 🚀 Algorithm Used

**Quick Sort (Divide and Conquer)**

### Steps:

1. Choose a pivot element
2. Partition the array such that elements smaller than pivot are on the left and larger on the right
3. Recursively apply quick sort to left and right subarrays

---

## 🧮 Time and Space Complexity

| Case    | Time Complexity |
| ------- | --------------- |
| Best    | `O(n log n)`    |
| Average | `O(n log n)`    |
| Worst   | `O(n²)`         |

* **Space Complexity:** `O(log n)` (recursive stack)

---

## 🛠️ Requirements

* Java 8 or later
* Any Java IDE or terminal

---

## 📂 Project Structure

```
QuickSort.java
README.md
```

---

## ▶️ How to Run

1. Compile:

   ```bash
   javac QuickSort.java
   ```
2. Run:

   ```bash
   java QuickSort
   ```

---

## 📋 Menu Options

```
1. Sort an Array
2. Exit
```

---

## ⌨️ Sample Input

```
Enter number of elements: 6
Elements: 10 7 8 9 1 5
```

---

## ✅ Sample Output

```
Original Array: 10 7 8 9 1 5
Sorted Array:   1 5 7 8 9 10
```

---

## 🧠 Key Concepts

* Divide and Conquer
* In-place Sorting
* Partitioning Logic
* Recursion

---

## 🔧 Customization Ideas

* Randomized Quick Sort
* Median-of-three pivot selection
* Iterative Quick Sort
* Count comparisons and swaps

---

## 📚 Applications

* Internal sorting
* System-level sorting routines
* Competitive programming
* Data analytics pipelines

---

## 📝 License

Free to use for academic, learning, and interview preparation.
