<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/pancake-sorting "Pancake Sorting")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/flip-binary-tree-to-match-preorder-traversal "Flip Binary Tree To Match Preorder Traversal")

## [970. Powerful Integers (Easy)](https://leetcode.com/problems/powerful-integers "强整数")

<p>Given two positive integers <code>x</code> and <code>y</code>, an integer is <em>powerful</em>&nbsp;if it is equal to <code>x^i + y^j</code>&nbsp;for&nbsp;some integers <code>i &gt;= 0</code> and <code>j &gt;= 0</code>.</p>

<p>Return a list of all <em>powerful</em> integers that have value less than or equal to <code>bound</code>.</p>

<p>You may return the answer in any order.&nbsp; In your answer, each value should occur at most once.</p>

<p>&nbsp;</p>

<div>
<p><strong>Example 1:</strong></p>

<pre>
<strong>Input: </strong>x = <span id="example-input-1-1">2</span>, y = <span id="example-input-1-2">3</span>, bound = <span id="example-input-1-3">10</span>
<strong>Output: </strong><span id="example-output-1">[2,3,4,5,7,9,10]</span>
<strong>Explanation: </strong>
2 = 2^0 + 3^0
3 = 2^1 + 3^0
4 = 2^0 + 3^1
5 = 2^1 + 3^1
7 = 2^2 + 3^1
9 = 2^3 + 3^0
10 = 2^0 + 3^2
</pre>

<div>
<p><strong>Example 2:</strong></p>

<pre>
<strong>Input: </strong>x = <span id="example-input-2-1">3</span>, y = <span id="example-input-2-2">5</span>, bound = <span id="example-input-2-3">15</span>
<strong>Output: </strong><span id="example-output-2">[2,4,6,8,10,14]</span>
</pre>
</div>
</div>

<p>&nbsp;</p>

<p><strong>Note:</strong></p>

<ul>
	<li><code>1 &lt;= x &lt;= 100</code></li>
	<li><code>1 &lt;= y&nbsp;&lt;= 100</code></li>
	<li><code>0 &lt;= bound&nbsp;&lt;= 10^6</code></li>
</ul>

### Related Topics
  [[Hash Table](https://github.com/openset/leetcode/tree/master/tag/hash-table/README.md)]
  [[Math](https://github.com/openset/leetcode/tree/master/tag/math/README.md)]
