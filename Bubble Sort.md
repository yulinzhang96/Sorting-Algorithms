**Description**

Traverse from left and compare adjacent elements and the higher one is placed at the right side. 
In this way, the largest element is moved to the rightmost end at first. 
This process is then continued to find the second largest and place it and so on until the data is sorted.

**Advantages**
1. Bubble sort is easy to understand and implement.
2. It does not require any additional memory space.
3. It is a stable sorting algorithm, meaning that elements with the same key value maintain their relative order in the sorted output.

**Disadvantages**
1. Bubble sort has a time complexity of O(n2) which makes it very slow for large data sets.
2. Bubble sort is a comparison-based sorting algorithm, which means that it requires a comparison operator to determine the relative order of elements in the input data set. It can limit the efficiency of the algorithm in certain cases.

**Time and Space Complexity**
* Time Complexity: O(n^2)
* Auxiliary Space: O(1)
