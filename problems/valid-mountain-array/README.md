<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/distinct-subsequences-ii "Distinct Subsequences II")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/di-string-match "DI String Match")

## [941. Valid Mountain Array (Easy)](https://leetcode.com/problems/valid-mountain-array "有效的山脉数组")

<p>Given an array <code>A</code> of integers, return <code>true</code> if and only if it is a <em>valid mountain array</em>.</p>

<p>Recall that A is a mountain array if and only if:</p>

<ul>
	<li><code>A.length &gt;= 3</code></li>
	<li>There exists some <code>i</code> with&nbsp;<code>0 &lt; i&nbsp;&lt; A.length - 1</code>&nbsp;such that:
	<ul>
		<li><code>A[0] &lt; A[1] &lt; ... A[i-1] &lt; A[i] </code></li>
		<li><code>A[i] &gt; A[i+1] &gt; ... &gt; A[A.length - 1]</code></li>
	</ul>
	</li>
</ul>

<br>
<img src="https://assets.leetcode.com/uploads/2019/10/20/hint_valid_mountain_array.png" width="500" />

<p>&nbsp;</p>

<p><strong>Example 1:</strong></p>

<pre>
<strong>Input: </strong><span id="example-input-1-1">[2,1]</span>
<strong>Output: </strong><span id="example-output-1">false</span>
</pre>

<div>
<p><strong>Example 2:</strong></p>

<pre>
<strong>Input: </strong><span id="example-input-2-1">[3,5,5]</span>
<strong>Output: </strong><span id="example-output-2">false</span>
</pre>

<div>
<p><strong>Example 3:</strong></p>

<pre>
<strong>Input: </strong><span id="example-input-3-1">[0,3,2,1]</span>
<strong>Output: </strong><span id="example-output-3">true</span></pre>
</div>
</div>

<p>&nbsp;</p>

<p><strong>Note:</strong></p>

<ol>
	<li><code>0 &lt;= A.length &lt;= 10000</code></li>
	<li><code>0 &lt;= A[i] &lt;= 10000&nbsp;</code></li>
</ol>

<div>
<p>&nbsp;</p>

<div>
<div>&nbsp;</div>
</div>
</div>

### Related Topics
  [[Array](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
It's very easy to keep track of a monotonically increasing or decreasing ordering of elements. You just need to be able to determine the start of the valley in the mountain and from that point onwards, it should be a valley i.e. no mini-hills after that. Use this information in regards to the values in the array and you will be able to come up with a straightforward solution.
</details>
