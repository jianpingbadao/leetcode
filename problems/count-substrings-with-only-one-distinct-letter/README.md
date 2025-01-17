<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/reformat-department-table "Reformat Department Table")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/before-and-after-puzzle "Before and After Puzzle")

## [1180. Count Substrings with Only One Distinct Letter (Easy)](https://leetcode.com/problems/count-substrings-with-only-one-distinct-letter "统计只含单一字母的子串")

<p>Given a string <code>S</code>,&nbsp;return the number of substrings that have&nbsp;only <strong>one distinct</strong> letter.</p>

<p>&nbsp;</p>
<p><strong>Example 1:</strong></p>

<pre>
<strong>Input:</strong> S = &quot;aaaba&quot;
<strong>Output:</strong> 8
<strong>Explanation: </strong>The substrings with one distinct letter are &quot;aaa&quot;, &quot;aa&quot;, &quot;a&quot;, &quot;b&quot;.
&quot;aaa&quot; occurs 1 time.
&quot;aa&quot; occurs 2 times.
&quot;a&quot; occurs 4 times.
&quot;b&quot; occurs 1 time.
So the answer is 1 + 2 + 4 + 1 = 8.
</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input:</strong> S = &quot;aaaaaaaaaa&quot;
<strong>Output:</strong> 55
</pre>

<p>&nbsp;</p>
<p><strong>Constraints:</strong></p>

<ul>
	<li><code>1 &lt;= S.length &lt;= 1000</code></li>
	<li><code>S[i]</code> consists of only lowercase English letters.</li>
</ul>

### Related Topics
  [[Math](https://github.com/openset/leetcode/tree/master/tag/math/README.md)]
  [[String](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
What if we divide the string into substrings containing only one distinct character with maximal lengths?
</details>

<details>
<summary>Hint 2</summary>
Now that you have sub-strings with only one distinct character, Try to come up with a formula that counts the number of its sub-strings.
</details>

<details>
<summary>Hint 3</summary>
Alternatively, Observe that the constraints are small so you can use brute force.
</details>
