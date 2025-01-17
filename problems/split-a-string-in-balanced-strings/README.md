<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/count-vowels-permutation "Count Vowels Permutation")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/queens-that-can-attack-the-king "Queens That Can Attack the King")

## [1221. Split a String in Balanced Strings (Easy)](https://leetcode.com/problems/split-a-string-in-balanced-strings "分割平衡字符串")

<p><i data-stringify-type="italic">Balanced</i>&nbsp;strings are those who have equal quantity of &#39;L&#39; and &#39;R&#39; characters.</p>

<p>Given a balanced string&nbsp;<code data-stringify-type="code">s</code>&nbsp;split it in the maximum amount of balanced strings.</p>

<p>Return the maximum amount of splitted balanced strings.</p>

<p>&nbsp;</p>
<p><strong>Example 1:</strong></p>

<pre>
<strong>Input:</strong> s = &quot;RLRRLLRLRL&quot;
<strong>Output:</strong> 4
<strong>Explanation: </strong>s can be split into &quot;RL&quot;, &quot;RRLL&quot;, &quot;RL&quot;, &quot;RL&quot;, each substring contains same number of &#39;L&#39; and &#39;R&#39;.
</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input:</strong> s = &quot;RLLLLRRRLR&quot;
<strong>Output:</strong> 3
<strong>Explanation: </strong>s can be split into &quot;RL&quot;, &quot;LLLRRR&quot;, &quot;LR&quot;, each substring contains same number of &#39;L&#39; and &#39;R&#39;.
</pre>

<p><strong>Example 3:</strong></p>

<pre>
<strong>Input:</strong> s = &quot;LLLLRRRR&quot;
<strong>Output:</strong> 1
<strong>Explanation: </strong>s can be split into &quot;LLLLRRRR&quot;.
</pre>

<p><strong>Example 4:</strong></p>

<pre>
<strong>Input:</strong> s = &quot;RLRRRLLRLL&quot;
<strong>Output:</strong> 2
<strong>Explanation: </strong>s can be split into &quot;RL&quot;, &quot;RRRLLRLL&quot;, since each substring contains an equal number of &#39;L&#39; and &#39;R&#39;
</pre>

<p>&nbsp;</p>
<p><strong>Constraints:</strong></p>

<ul>
	<li><code>1 &lt;= s.length &lt;= 1000</code></li>
	<li><code>s[i] = &#39;L&#39; or &#39;R&#39;</code></li>
</ul>

### Related Topics
  [[Greedy](https://github.com/openset/leetcode/tree/master/tag/greedy/README.md)]
  [[String](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
Loop from left to right maintaining a balance variable when it gets an L increase it by one otherwise decrease it by one.
</details>

<details>
<summary>Hint 2</summary>
Whenever the balance variable reaches zero then we increase the answer by one.
</details>
