<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/candy-crush "Candy Crush")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/split-linked-list-in-parts "Split Linked List in Parts")

## [724. Find Pivot Index (Easy)](https://leetcode.com/problems/find-pivot-index "寻找数组的中心索引")

<p>Given an array of integers <code>nums</code>, write a method that returns the &quot;pivot&quot; index of this array.</p>

<p>We define the pivot index as the index where the sum of the numbers to the left of the index is equal to the sum of the numbers to the right of the index.</p>

<p>If no such index exists, we should return -1. If there are multiple pivot indexes, you should return the left-most pivot index.</p>

<p><b>Example 1:</b></p>

<pre>
<b>Input:</b> 
nums = [1, 7, 3, 6, 5, 6]
<b>Output:</b> 3
<b>Explanation:</b> 
The sum of the numbers to the left of index 3 (nums[3] = 6) is equal to the sum of numbers to the right of index 3.
Also, 3 is the first index where this occurs.
</pre>

<p>&nbsp;</p>

<p><b>Example 2:</b></p>

<pre>
<b>Input:</b> 
nums = [1, 2, 3]
<b>Output:</b> -1
<b>Explanation:</b> 
There is no index that satisfies the conditions in the problem statement.
</pre>

<p>&nbsp;</p>

<p><b>Note:</b></p>

<ul>
	<li>The length of <code>nums</code> will be in the range <code>[0, 10000]</code>.</li>
	<li>Each element <code>nums[i]</code> will be an integer in the range <code>[-1000, 1000]</code>.</li>
</ul>

<p>&nbsp;</p>

### Related Topics
  [[Array](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]

### Similar Questions
  1. [Subarray Sum Equals K](https://github.com/openset/leetcode/tree/master/problems/subarray-sum-equals-k) (Medium)

### Hints
<details>
<summary>Hint 1</summary>
We can precompute prefix sums P[i] = nums[0] + nums[1] + ... + nums[i-1].
Then for each index, the left sum is P[i], and the right sum is P[P.length - 1] - P[i] - nums[i].
</details>
