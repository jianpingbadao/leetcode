<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/intersection-of-three-sorted-arrays "Intersection of Three Sorted Arrays")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/stepping-numbers "Stepping Numbers")

## [1214. Two Sum BSTs (Medium)](https://leetcode.com/problems/two-sum-bsts "查找两棵二叉搜索树之和")

<p>Given two binary search trees, return <code>True</code>&nbsp;if and only if there is a node in the first tree and a node in the second tree whose values&nbsp;sum up to a given integer&nbsp;<code>target</code>.</p>

<p>&nbsp;</p>

<p><strong>Example 1:</strong></p>

<p><strong><img alt="" src="https://assets.leetcode.com/uploads/2019/05/31/1368_1_a2.png" style="width: 150px; height: 140px;" /><img alt="" src="https://assets.leetcode.com/uploads/2019/05/31/1368_1_b.png" style="width: 150px; height: 136px;" /></strong></p>

<pre>
<strong>Input: </strong>root1 = <span id="example-input-1-1">[2,1,4]</span>, root2 = <span id="example-input-1-2">[1,0,3]</span>, target = <span id="example-input-1-3">5</span>
<strong>Output: </strong><span id="example-output-1">true</span>
<b>Explanation: </b>2 and 3 sum up to 5.
</pre>

<div>
<p><strong>Example 2:</strong></p>

<p><strong><img alt="" src="https://assets.leetcode.com/uploads/2019/05/31/1368_2_a.png" style="width: 150px; height: 137px;" /><img alt="" src="https://assets.leetcode.com/uploads/2019/05/31/1368_2_b.png" style="width: 150px; height: 168px;" /></strong></p>

<pre>
<strong>Input: </strong>root1 = <span id="example-input-2-1">[0,-10,10]</span>, root2 = <span id="example-input-2-2">[5,1,7,0,2]</span>, target = <span id="example-input-2-3">18</span>
<strong>Output: </strong><span id="example-output-2">false</span></pre>
</div>

<p>&nbsp;</p>

<p><strong>Note:</strong></p>

<ol>
	<li>Each tree has at most <code>5000</code> nodes.</li>
	<li><code>-10^9 &lt;= target, node.val &lt;= 10^9</code></li>
</ol>

### Related Topics
  [[Binary Search Tree](https://github.com/openset/leetcode/tree/master/tag/binary-search-tree/README.md)]

### Similar Questions
  1. [Two Sum IV - Input is a BST](https://github.com/openset/leetcode/tree/master/problems/two-sum-iv-input-is-a-bst) (Easy)

### Hints
<details>
<summary>Hint 1</summary>
How can you reduce this problem to the classical Two Sum problem?
</details>

<details>
<summary>Hint 2</summary>
Do an in-order traversal of each tree to convert them to sorted arrays.
</details>

<details>
<summary>Hint 3</summary>
Solve the classical Two Sum problem.
</details>
