<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/maximum-length-of-pair-chain "Maximum Length of Pair Chain")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/replace-words "Replace Words")

## [647. Palindromic Substrings (Medium)](https://leetcode.com/problems/palindromic-substrings "回文子串")

<p>Given a string, your task is to count how many palindromic substrings in this string.</p>

<p>The substrings with different start indexes or end indexes are counted as different substrings even they consist of same characters.</p>

<p><b>Example 1:</b></p>

<pre>
<b>Input:</b> &quot;abc&quot;
<b>Output:</b> 3
<b>Explanation:</b> Three palindromic strings: &quot;a&quot;, &quot;b&quot;, &quot;c&quot;.
</pre>

<p>&nbsp;</p>

<p><b>Example 2:</b></p>

<pre>
<b>Input:</b> &quot;aaa&quot;
<b>Output:</b> 6
<b>Explanation:</b> Six palindromic strings: &quot;a&quot;, &quot;a&quot;, &quot;a&quot;, &quot;aa&quot;, &quot;aa&quot;, &quot;aaa&quot;.
</pre>

<p>&nbsp;</p>

<p><b>Note:</b></p>

<ol>
	<li>The input string length won&#39;t exceed 1000.</li>
</ol>

<p>&nbsp;</p>

### Related Topics
  [[String](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]
  [[Dynamic Programming](https://github.com/openset/leetcode/tree/master/tag/dynamic-programming/README.md)]

### Similar Questions
  1. [Longest Palindromic Substring](https://github.com/openset/leetcode/tree/master/problems/longest-palindromic-substring) (Medium)
  1. [Longest Palindromic Subsequence](https://github.com/openset/leetcode/tree/master/problems/longest-palindromic-subsequence) (Medium)
  1. [Palindromic Substrings](https://github.com/openset/leetcode/tree/master/problems/palindromic-substrings) (Medium)

### Hints
<details>
<summary>Hint 1</summary>
How can we reuse a previously computed palindrome to compute a larger palindrome?
</details>

<details>
<summary>Hint 2</summary>
If “aba” is a palindrome, is “xabax” and palindrome? Similarly is “xabay” a palindrome?
</details>

<details>
<summary>Hint 3</summary>
Complexity based hint:</br>
If we use brute-force and check whether for every start and end position a substring is a palindrome we have O(n^2) start - end pairs and O(n) palindromic checks. Can we reduce the time for palindromic checks to O(1) by reusing some previous computation?
</details>
