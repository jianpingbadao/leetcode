<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/loud-and-rich "Loud and Rich")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/car-fleet "Car Fleet")

## [852. Peak Index in a Mountain Array (Easy)](https://leetcode.com/problems/peak-index-in-a-mountain-array "山脉数组的峰顶索引")

<p>Let&#39;s call an array <code>A</code> a <em>mountain</em>&nbsp;if the following properties hold:</p>

<ul>
	<li><code>A.length &gt;= 3</code></li>
	<li>There exists some <code>0 &lt; i&nbsp;&lt; A.length - 1</code> such that <code>A[0] &lt; A[1] &lt; ... A[i-1] &lt; A[i] &gt; A[i+1] &gt; ... &gt; A[A.length - 1]</code></li>
</ul>

<p>Given an array that is definitely a mountain, return any&nbsp;<code>i</code>&nbsp;such that&nbsp;<code>A[0] &lt; A[1] &lt; ... A[i-1] &lt; A[i] &gt; A[i+1] &gt; ... &gt; A[A.length - 1]</code>.</p>

<p><strong>Example 1:</strong></p>

<pre>
<strong>Input: </strong><span id="example-input-1-1">[0,1,0]</span>
<strong>Output: </strong><span id="example-output-1">1</span>
</pre>

<div>
<p><strong>Example 2:</strong></p>

<pre>
<strong>Input: </strong><span id="example-input-2-1">[0,2,1,0]</span>
<strong>Output: </strong><span id="example-output-2">1</span></pre>
</div>

<p><strong>Note:</strong></p>

<ol>
	<li><code>3 &lt;= A.length &lt;= 10000</code></li>
	<li><code><font face="monospace">0 &lt;= A[i] &lt;= 10^6</font></code></li>
	<li>A&nbsp;is a mountain, as defined above.</li>
</ol>

### Related Topics
  [[Binary Search](https://github.com/openset/leetcode/tree/master/tag/binary-search/README.md)]

### Similar Questions
  1. [Find Peak Element](https://github.com/openset/leetcode/tree/master/problems/find-peak-element) (Medium)
