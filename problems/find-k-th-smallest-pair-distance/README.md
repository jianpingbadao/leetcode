<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/maximum-length-of-repeated-subarray "Maximum Length of Repeated Subarray")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/longest-word-in-dictionary "Longest Word in Dictionary")

## [719. Find K-th Smallest Pair Distance (Hard)](https://leetcode.com/problems/find-k-th-smallest-pair-distance "找出第 k 小的距离对")

<p>Given an integer array, return the k-th smallest <b>distance</b> among all the pairs. The distance of a pair (A, B) is defined as the absolute difference between A and B. </p>

<p><b>Example 1:</b><br />
<pre>
<b>Input:</b>
nums = [1,3,1]
k = 1
<b>Output: 0</b> 
<b>Explanation:</b>
Here are all the pairs:
(1,3) -> 2
(1,1) -> 0
(3,1) -> 2
Then the 1st smallest distance pair is (1,1), and its distance is 0.
</pre>
</p>

<p><b>Note:</b><br>
<ol>
<li><code>2 <= len(nums) <= 10000</code>.</li>
<li><code>0 <= nums[i] < 1000000</code>.</li>
<li><code>1 <= k <= len(nums) * (len(nums) - 1) / 2</code>.</li>
</ol>
</p>

### Related Topics
  [[Heap](https://github.com/openset/leetcode/tree/master/tag/heap/README.md)]
  [[Array](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[Binary Search](https://github.com/openset/leetcode/tree/master/tag/binary-search/README.md)]

### Similar Questions
  1. [Find K Pairs with Smallest Sums](https://github.com/openset/leetcode/tree/master/problems/find-k-pairs-with-smallest-sums) (Medium)
  1. [Kth Smallest Element in a Sorted Matrix](https://github.com/openset/leetcode/tree/master/problems/kth-smallest-element-in-a-sorted-matrix) (Medium)
  1. [Find K Closest Elements](https://github.com/openset/leetcode/tree/master/problems/find-k-closest-elements) (Medium)
  1. [Kth Smallest Number in Multiplication Table](https://github.com/openset/leetcode/tree/master/problems/kth-smallest-number-in-multiplication-table) (Hard)
  1. [K-th Smallest Prime Fraction](https://github.com/openset/leetcode/tree/master/problems/k-th-smallest-prime-fraction) (Hard)

### Hints
<details>
<summary>Hint 1</summary>
Binary search for the answer.  How can you check how many pairs have distance <= X?
</details>
