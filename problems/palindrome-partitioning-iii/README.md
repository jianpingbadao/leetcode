<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/count-square-submatrices-with-all-ones "Count Square Submatrices with All Ones")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/traffic-light-controlled-intersection "Traffic Light Controlled Intersection")

## [1278. Palindrome Partitioning III (Hard)](https://leetcode.com/problems/palindrome-partitioning-iii "分割回文串 III")

<p>You are given a string&nbsp;<code>s</code> containing lowercase letters and an integer <code>k</code>. You need to :</p>

<ul>
	<li>First, change some characters of <code>s</code>&nbsp;to other lowercase English letters.</li>
	<li>Then divide <code>s</code>&nbsp;into <code>k</code> non-empty disjoint substrings such that each substring is palindrome.</li>
</ul>

<p>Return the minimal number of characters that you need to change&nbsp;to divide the string.</p>

<p>&nbsp;</p>
<p><strong>Example 1:</strong></p>

<pre>
<strong>Input:</strong> s = &quot;abc&quot;, k = 2
<strong>Output:</strong> 1
<strong>Explanation:</strong>&nbsp;You can split the string into &quot;ab&quot; and &quot;c&quot;, and change 1 character in &quot;ab&quot; to make it palindrome.
</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input:</strong> s = &quot;aabbc&quot;, k = 3
<strong>Output:</strong> 0
<strong>Explanation:</strong>&nbsp;You can split the string into &quot;aa&quot;, &quot;bb&quot; and &quot;c&quot;, all of them are palindrome.</pre>

<p><strong>Example 3:</strong></p>

<pre>
<strong>Input:</strong> s = &quot;leetcode&quot;, k = 8
<strong>Output:</strong> 0
</pre>

<p>&nbsp;</p>
<p><strong>Constraints:</strong></p>

<ul>
	<li><code>1 &lt;= k &lt;= s.length &lt;= 100</code>.</li>
	<li><code>s</code>&nbsp;only contains lowercase English letters.</li>
</ul>

### Related Topics
  [[Dynamic Programming](https://github.com/openset/leetcode/tree/master/tag/dynamic-programming/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
For each substring calculate the minimum number of steps to make it palindrome and store it in a table.
</details>

<details>
<summary>Hint 2</summary>
Create a dp(pos, cnt) which means the minimum number of characters changed for the suffix of s starting on pos splitting the suffix on cnt chunks.
</details>
