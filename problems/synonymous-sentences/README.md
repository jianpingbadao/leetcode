<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/smallest-common-region "Smallest Common Region")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/handshakes-that-dont-cross "Handshakes That Don't Cross")

## [1258. Synonymous Sentences (Medium)](https://leetcode.com/problems/synonymous-sentences "近义词句子")

Given a list of pairs of equivalent words&nbsp;<code>synonyms</code> and a sentence <code>text</code>,&nbsp;Return all possible synonymous sentences <strong>sorted lexicographically</strong>.
<p>&nbsp;</p>
<p><strong>Example 1:</strong></p>

<pre>
<strong>Input:
</strong>synonyms = [[&quot;happy&quot;,&quot;joy&quot;],[&quot;sad&quot;,&quot;sorrow&quot;],[&quot;joy&quot;,&quot;cheerful&quot;]],
text = &quot;I am happy today but was sad yesterday&quot;
<strong>Output:
</strong>[&quot;I am cheerful today but was sad yesterday&quot;,
​​​​​​​&quot;I am cheerful today but was sorrow yesterday&quot;,
&quot;I am happy today but was sad yesterday&quot;,
&quot;I am happy today but was sorrow yesterday&quot;,
&quot;I am joy today but was sad yesterday&quot;,
&quot;I am joy today but was sorrow yesterday&quot;]
</pre>

<p>&nbsp;</p>
<p><strong>Constraints:</strong></p>

<ul>
	<li><code>0 &lt;=&nbsp;synonyms.length &lt;= 10</code></li>
	<li><code>synonyms[i].length == 2</code></li>
	<li><code>synonyms[0] != synonyms[1]</code></li>
	<li>All words consist of at most <code>10</code> English letters only.</li>
	<li><code>text</code>&nbsp;is a single space separated sentence of at most <code>10</code> words.</li>
</ul>

### Related Topics
  [[Backtracking](https://github.com/openset/leetcode/tree/master/tag/backtracking/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
Find all synonymous groups of words.
</details>

<details>
<summary>Hint 2</summary>
Use union-find data structure.
</details>

<details>
<summary>Hint 3</summary>
By backtracking, generate all possible statements.
</details>
