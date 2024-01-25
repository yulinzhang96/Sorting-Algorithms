**Description**

Bucket Sort is a sorting algorithm that divides the unsorted array elements into several groups called buckets. Each bucket is then sorted by using any of the suitable sorting algorithms or recursively applying the same bucket algorithm.

Finally, the sorted buckets are combined to form a final sorted array.

Bucket sort is used when:

    1. Input is uniformly distributed over a range.
    2. There are floating point values.

**Implementation**

Create n empty buckets (Or lists) and do the following for every array element arr[i].
Insert arr[i] into bucket[n*array[i]]
Sort individual buckets using insertion sort or any other common sorting algorithms
Concatenate all sorted buckets.

**Time and Space Complexity**
* Time Complexity: O(n)
* Auxiliary Space: O(n+k)
