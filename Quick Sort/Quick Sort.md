**Description**

Quicksort is a sorting algorithm based on the divide and conquer approach where
1. An array is divided into subarrays by selecting a pivot element (element selected from the array). While dividing the array, the pivot element should be positioned in such a way that elements less than pivot are kept on the left side and elements greater than pivot are on the right side of the pivot.
2. The left and right subarrays are also divided using the same approach. This process continues until each subarray contains a single element.
3. At this point, elements are already sorted. Finally, elements are combined to form a sorted array.

**Advantages**

1. It is a divide-and-conquer algorithm that makes it easier to solve problems.
2. It is efficient on large data sets.
3. It has a low overhead, as it only requires a small amount of memory to function.

**Disadvantages**

1. It has a worst-case time complexity of O(n^2), which occurs when the pivot is chosen poorly.
2. It is not a good choice for small data sets.
3. It is not a stable sort, meaning that if two elements have the same key, their relative order will not be preserved in the sorted output in case of quick sort, because here we are swapping elements according to the pivot’s position (without considering their original positions).

**Time and Space Complexity**

* Time Complexity: O(n*log(n))
* Auxiliary Space: O(log(n))
