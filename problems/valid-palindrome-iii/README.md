<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/stepping-numbers "Stepping Numbers")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/play-with-chips "Play with Chips")

## [1216. Valid Palindrome III (Hard)](https://leetcode.com/problems/valid-palindrome-iii "验证回文字符串 III")

<p>Given a string <code>s</code>&nbsp;and an integer&nbsp;<code>k</code>, find out if the given string is&nbsp;a&nbsp;<em>K-Palindrome</em> or not.</p>

<p>A string is K-Palindrome if it can be&nbsp;transformed&nbsp;into a palindrome by removing at most <code>k</code> characters from it.</p>

<p>&nbsp;</p>
<p><strong>Example 1:</strong></p>

<pre>
<strong>Input:</strong> s = &quot;abcdeca&quot;, k = 2
<strong>Output:</strong> true
<strong>Explanation: </strong>Remove &#39;b&#39; and &#39;e&#39; characters.
</pre>

<p>&nbsp;</p>
<p><strong>Constraints:</strong></p>

<ul>
	<li><code>1 &lt;= s.length &lt;= 1000</code></li>
	<li><code>s</code>&nbsp;has only lowercase English letters.</li>
	<li><code>1 &lt;= k&nbsp;&lt;= s.length</code></li>
</ul>

### Related Topics
  [[String](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]
  [[Dynamic Programming](https://github.com/openset/leetcode/tree/master/tag/dynamic-programming/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
Can you reduce this problem to a classic problem?
</details>

<details>
<summary>Hint 2</summary>
The problem is equivalent to finding any palindromic subsequence of length at least N-K where N is the length of the string.
</details>

<details>
<summary>Hint 3</summary>
Try to find the longest palindromic subsequence.
</details>

<details>
<summary>Hint 4</summary>
Use DP to do that.
</details>
