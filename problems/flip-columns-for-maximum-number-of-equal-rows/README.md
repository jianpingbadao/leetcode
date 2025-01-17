<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/greatest-common-divisor-of-strings "Greatest Common Divisor of Strings")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/adding-two-negabinary-numbers "Adding Two Negabinary Numbers")

## [1072. Flip Columns For Maximum Number of Equal Rows (Medium)](https://leetcode.com/problems/flip-columns-for-maximum-number-of-equal-rows "按列翻转得到最大值等行数")

<p>Given a <code>matrix</code> consisting of 0s and 1s, we may choose any number of columns in the matrix and flip <strong>every</strong>&nbsp;cell in that column.&nbsp; Flipping a cell changes the value of that cell from 0 to 1 or from 1 to 0.</p>

<p>Return the maximum number of rows that have all values equal after some number of flips.</p>

<p>&nbsp;</p>

<ol>
</ol>

<div>
<p><strong>Example 1:</strong></p>

<pre>
<strong>Input: </strong><span id="example-input-1-1">[[0,1],[1,1]]</span>
<strong>Output: </strong><span id="example-output-1">1</span>
<strong>Explanation: </strong>After flipping no values, 1 row has all values equal.
</pre>

<div>
<p><strong>Example 2:</strong></p>

<pre>
<strong>Input: </strong><span id="example-input-2-1">[[0,1],[1,0]]</span>
<strong>Output: </strong><span id="example-output-2">2</span>
<strong>Explanation: </strong>After flipping values in the first column, both rows have equal values.
</pre>

<div>
<p><strong>Example 3:</strong></p>

<pre>
<strong>Input: </strong><span id="example-input-3-1">[[0,0,0],[0,0,1],[1,1,0]]</span>
<strong>Output: </strong><span id="example-output-3">2</span>
<strong>Explanation: </strong>After flipping values in the first two columns, the last two rows have equal values.
</pre>

<p>&nbsp;</p>

<p><strong>Note:</strong></p>

<ol>
	<li><code>1 &lt;= matrix.length &lt;= 300</code></li>
	<li><code>1 &lt;= matrix[i].length &lt;= 300</code></li>
	<li>All <code>matrix[i].length</code>&#39;s are equal</li>
	<li><code>matrix[i][j]</code> is&nbsp;<code>0</code> or <code>1</code></li>
</ol>
</div>
</div>
</div>

### Related Topics
  [[Hash Table](https://github.com/openset/leetcode/tree/master/tag/hash-table/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
Flipping a subset of columns is like doing a bitwise XOR of some number K onto each row.  We want rows X with X ^ K = all 0s or all 1s.  This is the same as X = X^K ^K = (all 0s or all 1s) ^ K, so we want to count rows that have opposite bits set.  For example, if K = 1, then we count rows X = (00000...001, or 1111....110).
</details>
