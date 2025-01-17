<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/fixed-point "Fixed Point")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/campus-bikes-ii "Campus Bikes II")

## [1065. Index Pairs of a String (Easy)](https://leetcode.com/problems/index-pairs-of-a-string "字符串的索引对")

<p>Given a <code>text</code>&nbsp;string and <code>words</code> (a list of strings), return all index pairs <code>[i, j]</code> so that the substring <code>text[i]...text[j]</code>&nbsp;is in the list of <code>words</code>.</p>

<p>&nbsp;</p>

<p><strong>Example 1:</strong></p>

<pre>
<strong>Input: </strong>text = <span id="example-input-1-1">&quot;thestoryofleetcodeandme&quot;</span>, words = <span id="example-input-1-2">[&quot;story&quot;,&quot;fleet&quot;,&quot;leetcode&quot;]</span>
<strong>Output: </strong><span id="example-output-1">[[3,7],[9,13],[10,17]]</span>
</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input: </strong>text = <span id="example-input-2-1">&quot;ababa&quot;</span>, words = <span id="example-input-2-2">[&quot;aba&quot;,&quot;ab&quot;]</span>
<strong>Output: </strong><span id="example-output-2">[[0,1],[0,2],[2,3],[2,4]]</span>
<strong>Explanation: </strong>
Notice that matches can overlap, see &quot;aba&quot; is found in [0,2] and [2,4].
</pre>

<p>&nbsp;</p>

<p><strong>Note:</strong></p>

<ol>
	<li>All strings contains only lowercase English letters.</li>
	<li>It&#39;s guaranteed that all strings in <code>words</code> are different.</li>
	<li><code>1 &lt;= text.length &lt;= 100</code></li>
	<li><code>1 &lt;= words.length &lt;= 20</code></li>
	<li><code>1 &lt;= words[i].length &lt;= 50</code></li>
	<li>Return the pairs <code>[i,j]</code> in sorted order (i.e. sort them by their first coordinate in case of ties sort them by their second coordinate).</li>
</ol>

### Related Topics
  [[Trie](https://github.com/openset/leetcode/tree/master/tag/trie/README.md)]
  [[String](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
For each string of the set, look for matches and store those matches indices.
</details>
