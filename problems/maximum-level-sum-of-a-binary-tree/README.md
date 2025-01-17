<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/find-words-that-can-be-formed-by-characters "Find Words That Can Be Formed by Characters")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/as-far-from-land-as-possible "As Far from Land as Possible")

## [1161. Maximum Level Sum of a Binary Tree (Medium)](https://leetcode.com/problems/maximum-level-sum-of-a-binary-tree "最大层内元素和")

<p>Given the <code>root</code> of a binary tree, the level of its root is <code>1</code>,&nbsp;the level of its children is <code>2</code>,&nbsp;and so on.</p>

<p>Return the <strong>smallest</strong> level <code>X</code> such that the sum of all the values of nodes at level <code>X</code> is <strong>maximal</strong>.</p>

<p>&nbsp;</p>

<p><strong>Example 1:</strong></p>

<p><strong><img alt="" src="https://assets.leetcode.com/uploads/2019/05/03/capture.JPG" style="width: 200px; height: 175px;" /></strong></p>

<pre>
<strong>Input: </strong><span id="example-input-1-1">[1,7,0,7,-8,null,null]</span>
<strong>Output: </strong><span id="example-output-1">2</span>
<strong>Explanation: </strong>
Level 1 sum = 1.
Level 2 sum = 7 + 0 = 7.
Level 3 sum = 7 + -8 = -1.
So we return the level with the maximum sum which is level 2.
</pre>

<p>&nbsp;</p>

<p><strong>Note:</strong></p>

<ol>
	<li>The number of nodes in the given tree is between <code>1</code> and <code>10^4</code>.</li>
	<li><code>-10^5 &lt;= node.val &lt;= 10^5</code></li>
</ol>

### Related Topics
  [[Graph](https://github.com/openset/leetcode/tree/master/tag/graph/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
Calculate the sum for each level then find the level with the maximum sum.
</details>

<details>
<summary>Hint 2</summary>
How can you traverse the tree ?
</details>

<details>
<summary>Hint 3</summary>
How can you sum up the values for every level ?
</details>

<details>
<summary>Hint 4</summary>
Use DFS or BFS to traverse the tree keeping the level of each node, and sum up those values with a map or a frequency array.
</details>
