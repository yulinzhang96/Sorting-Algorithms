**Description**

Merge sort is one of the most efficient sorting algorithms. It is based on the divide-and-conquer strategy. Merge sort continuously cuts down a list into multiple sublists until each has only one item, then merges those sublists into a sorted list.

**Implementation**

It splits the input array in half, calls itself for each half, and then combines the two sorted parts. Merging two halves is done with the merge() method. Merge (array[], left, mid, right) is a crucial process that assumes array[left..mid] and array[mid+1..right]  are both sorted subarrays and merges them into one.

**Advantages**

1. Merge sort can efficiently sort a list in O(n*log(n)) time.
2. Merge sort can be used with linked lists without taking up any more space.
3. A merge sort algorithm is used to count the number of inversions in the list.
4. Merge sort is employed in external sorting.
5. It keeps the order of equal elements (stable).

**Disadvantages**

1. For small datasets, merge sort is slower than other sorting algorithms.
2. For the temporary array, mergesort requires an additional space of O(n).
3. Even if the array is sorted, the merge sort goes through the entire process.

**Time and Space Complexity**

* Time Complexity: O(n*log(n))
* Auxiliary Space: O(n)
