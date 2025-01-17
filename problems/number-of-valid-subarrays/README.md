<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/longest-repeating-substring "Longest Repeating Substring")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/fixed-point "Fixed Point")

## [1063. Number of Valid Subarrays (Hard)](https://leetcode.com/problems/number-of-valid-subarrays "有效子数组的数目")

<p>Given an array <code>A</code> of integers, return the number of <strong>non-empty continuous subarrays</strong> that satisfy the following condition:</p>

<p>The leftmost element of the subarray is not larger than other elements in the subarray.</p>

<p>&nbsp;</p>

<p><strong>Example 1:</strong></p>

<pre>
<strong>Input: </strong><span id="example-input-1-1">[1,4,2,5,3]</span>
<strong>Output: </strong><span id="example-output-1">11</span>
<strong>Explanation: </strong>There are 11 valid subarrays: [1],[4],[2],[5],[3],[1,4],[2,5],[1,4,2],[2,5,3],[1,4,2,5],[1,4,2,5,3].
</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input: </strong><span id="example-input-2-1">[3,2,1]</span>
<strong>Output: </strong><span id="example-output-2">3</span>
<strong>Explanation: </strong>The 3 valid subarrays are: [3],[2],[1].
</pre>

<p><strong>Example 3:</strong></p>

<pre>
<strong>Input: </strong><span id="example-input-3-1">[2,2,2]</span>
<strong>Output: </strong><span id="example-output-3">6</span>
<strong>Explanation: </strong>There are 6 valid subarrays: [2],[2],[2],[2,2],[2,2],[2,2,2].
</pre>

<p>&nbsp;</p>

<p><strong>Note:</strong></p>

<ol>
	<li><code>1 &lt;= A.length &lt;= 50000</code></li>
	<li><code>0 &lt;= A[i] &lt;= 100000</code></li>
</ol>

### Related Topics
  [[Stack](https://github.com/openset/leetcode/tree/master/tag/stack/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
Given a data structure that answers queries of the type to find the minimum in a range of an array (Range minimum query (RMQ) sparse table) in O(1) time. How can you solve this problem?
</details>

<details>
<summary>Hint 2</summary>
For each starting index do a binary search with an RMQ to find the ending possible position.
</details>
