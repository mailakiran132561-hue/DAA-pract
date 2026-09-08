# practials
pract-DAA-1
SUMMARY

1.Bubble Sort Repeatedly compares adjacent elements and swaps them if they are in the wrong order. Best case: O(n) Average/Worst case: O(n²) Space: O(1) 2.Selection Sort Finds the smallest element from the unsorted portion and places it at the correct position. Best/Average/Worst case: O(n²) Space: O(1) 3.Insertion Sort Builds the sorted array one element at a time by inserting each element into its proper position. Best case: O(n) Average/Worst case: O(n²) Space: O(1) 4.Merge Sort Divides the array into smaller parts, recursively sorts them, and merges the sorted parts. Best/Average/Worst case: O(n log n) Space: O(n) 5.Quick Sort Selects a pivot and divides the elements into smaller and larger groups, then recursively sorts them. Best/Average case: O(n log n) Worst case: O(n²) Space: O(n) for this particular implementation.

Each algorithm takes numbers from the user, sorts them, displays the sorted array, and measures execution time using Python's

CONCLUSION:

The notebook demonstrates how different sorting algorithms perform and highlights the importance of time and space complexity. Bubble Sort, Selection Sort, and Insertion Sort are simple and easy to understand but become inefficient for large datasets because their average or worst-case performance is O(n²). Merge Sort provides consistently good performance of O(n log n), making it suitable for large datasets. Quick Sort also generally performs very efficiently with O(n log n) average performance, although its worst case can reach O(n²).

Overall, Merge Sort and Quick Sort are more suitable for large inputs, while Insertion Sort can be effective for small or nearly sorted arrays. The execution-time measurements in the notebook can be used to experimentally observe these theoretical difference

pract-DAA-2
SUMMARY:

1.Linear Search Checks each element of the array one by one until the target element is found. It works on both sorted and unsorted arrays. Time Complexity: O(n) The algorithm returns the index of the target if it is found; otherwise, it returns -1. The program also measures the execution time using time.perf_counter(). 2.Binary Search Searches for an element by repeatedly dividing the search range into two halves. The input array must be sorted for binary search to work correctly. Time Complexity: O(log n) It compares the target with the middle element and eliminates half of the remaining elements after each comparison. Like linear search, the program displays whether the element was found and measures its execution time.

CONCLUSION:

The notebook demonstrates the difference between Linear Search and Binary Search in terms of searching technique and efficiency. Linear Search is simple and can be used with both sorted and unsorted data, but its O(n) time complexity makes it slower for large datasets.

Binary Search is significantly more efficient for large sorted datasets because it reduces the search space by half during every iteration, resulting in O(log n) time complexity. However, it requires the input data to be sorted before searching.

Overall, Linear Search is suitable for small or unsorted datasets, while Binary Search is preferable for large, sorted datasets because of its much faster search performance.

pract-DAA-3
summary:

The practical implements Heap Sort using Min-Heap and Max-Heap in Python with the heapq library. The Min-Heap implementation sorts the elements in ascending order, while the Max-Heap implementation sorts them in descending order by using negative values. The program also measures the execution time using time.perf_counter() and displays the sorted array along with the time complexity.

CONCLUSION:

Thus, Heap Sort is an efficient comparison-based sorting technique based on the heap data structure. Both Min-Heap and Max-Heap approaches provide a time complexity of O(n log n) for best, average, and worst cases. The practical demonstrates how heaps can be effectively used to sort data in both ascending and descending order while also analyzing the algorithm's execution time.

pract-DAA-4
summary:

The program calculates the factorial of a given number using two approaches: iterative and recursive methods. The iterative method uses a for loop to multiply numbers from 1 to n, while the recursive method repeatedly calls itself with n-1 until it reaches the base case of 0 or 1. Both methods produce the same factorial result and have a time complexity of O(n). The execution time of each method is also measured using Python's time module.

CONCLUSION:

Both iterative and recursive methods successfully calculate the factorial of a number. The iterative method is generally more memory-efficient because it does not use the function call stack, whereas the recursive method is simpler and demonstrates the concept of recursion. For large values of n, the iterative approach is usually preferred because recursion can cause stack-depth limitations. Thus, both methods have the same time complexity, but the iterative method has an advantage in terms of space efficiency.
