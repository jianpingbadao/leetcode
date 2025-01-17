<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/invalid-transactions "Invalid Transactions")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/remove-zero-sum-consecutive-nodes-from-linked-list "Remove Zero Sum Consecutive Nodes from Linked List")

## [1170. Compare Strings by Frequency of the Smallest Character (Easy)](https://leetcode.com/problems/compare-strings-by-frequency-of-the-smallest-character "比较字符串最小字母出现频次")

<p>Let&#39;s define a function <code>f(s)</code> over a non-empty string <code>s</code>, which calculates the frequency of the smallest character in <code>s</code>. For example,&nbsp;if <code>s = &quot;dcce&quot;</code> then <code>f(s) = 2</code> because the smallest character is <code>&quot;c&quot;</code> and its frequency is 2.</p>

<p>Now, given string arrays <code>queries</code>&nbsp;and <code>words</code>, return an integer array <code>answer</code>, where each <code>answer[i]</code>&nbsp;is the number of words such that <code>f(queries[i])</code>&nbsp;&lt; <code>f(W)</code>, where <code>W</code>&nbsp;is a word in <code>words</code>.</p>

<p>&nbsp;</p>
<p><strong>Example 1:</strong></p>

<pre>
<strong>Input:</strong> queries = [&quot;cbd&quot;], words = [&quot;zaaaz&quot;]
<strong>Output:</strong> [1]
<strong>Explanation:</strong> On the first query we have f(&quot;cbd&quot;) = 1, f(&quot;zaaaz&quot;) = 3 so f(&quot;cbd&quot;) &lt; f(&quot;zaaaz&quot;).
</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input:</strong> queries = [&quot;bbb&quot;,&quot;cc&quot;], words = [&quot;a&quot;,&quot;aa&quot;,&quot;aaa&quot;,&quot;aaaa&quot;]
<strong>Output:</strong> [1,2]
<strong>Explanation:</strong> On the first query only f(&quot;bbb&quot;) &lt; f(&quot;aaaa&quot;). On the second query both f(&quot;aaa&quot;) and f(&quot;aaaa&quot;) are both &gt; f(&quot;cc&quot;).
</pre>

<p>&nbsp;</p>
<p><strong>Constraints:</strong></p>

<ul>
	<li><code>1 &lt;= queries.length &lt;= 2000</code></li>
	<li><code>1 &lt;= words.length &lt;= 2000</code></li>
	<li><code>1 &lt;= queries[i].length, words[i].length &lt;= 10</code></li>
	<li><code>queries[i][j]</code>, <code>words[i][j]</code> are English lowercase letters.</li>
</ul>

### Related Topics
  [[Array](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[String](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
For each string from words calculate the leading count and store it in an array, then sort the integer array.
</details>

<details>
<summary>Hint 2</summary>
For each string from queries calculate the leading count "p" and in base of the sorted array calculated on the step 1 do a binary search to count the number of items greater than "p".
</details>
