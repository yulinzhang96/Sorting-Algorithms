**Description**

Radix sort is a sorting algorithm that sorts the elements by first grouping the individual digits of the same place value. Then, sort the elements according to their increasing/decreasing order.

Suppose, we have an array of 8 elements. First, we will sort elements based on the value of the unit place. Then, we will sort elements based on the value of the tenth place. This process goes on until the last significant place.

**Advantages**

1. Radix sort has linear time complexity which is better than O(nlog n) of comparative sorting algorithms.

**Disadvantages**

1. If we take very large digit numbers or the number of other bases like 32-bit and 64-bit numbers then it can perform in linear time however the intermediate sort takes large space.

**Time and Space Complexity**

* Time Complexity: O(n+k)
* Auxiliary Space: O(m), where m is the largest element
