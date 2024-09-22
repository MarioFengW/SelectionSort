# SelectionSort Algorithm in C++

## Description
SelectionSort is a comparison-based algorithm that divides the array into two parts: a sorted and an unsorted part. It repeatedly selects the smallest (or largest) element from the unsorted part and swaps it with the first unsorted element, progressively growing the sorted section. While SelectionSort has a poor time complexity compared to more advanced algorithms, it is useful for small datasets and educational purposes.

## Algorithm Overview
1. **Select the minimum element** from the unsorted portion of the array.
2. **Swap** it with the first unsorted element.
3. **Move the boundary** of the sorted section forward by one.
4. Repeat until the entire array is sorted.

### Characteristics:
- SelectionSort is **not stable**, meaning it doesn't maintain the relative order of equal elements.
- It makes fewer swaps than other algorithms like BubbleSort, but more comparisons.

## Code Explanation
- **swap function**: Swaps two elements in the array.
- **selectionSort function**: Finds the minimum element and swaps it with the correct position.
- **Driver code**: Handles input/output and initiates the sorting process.

## Time and Space Complexity
- **Time Complexity**:
  - **Best case**: `O(n^2)`
  - **Average case**: `O(n^2)`
  - **Worst case**: `O(n^2)`
  
- **Space Complexity**: `O(1)` – Sorting is done in place.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/SelectionSort.git
