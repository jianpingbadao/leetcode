<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/sudoku-solver "Sudoku Solver")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/combination-sum "Combination Sum")

## [38. Count and Say (Easy)](https://leetcode.com/problems/count-and-say "报数")

<p>The count-and-say sequence is the sequence of integers with the first five terms as following:</p>

<pre>
1.     1
2.     11
3.     21
4.     1211
5.     111221
</pre>

<p><code>1</code> is read off as <code>&quot;one 1&quot;</code> or <code>11</code>.<br />
<code>11</code> is read off as <code>&quot;two 1s&quot;</code> or <code>21</code>.<br />
<code>21</code> is read off as <code>&quot;one 2</code>, then <code>one 1&quot;</code> or <code>1211</code>.</p>

<p>Given an integer <i>n</i>&nbsp;where 1 &le; <em>n</em> &le; 30, generate the <i>n</i><sup>th</sup> term of the count-and-say sequence.</p>

<p>Note: Each term of the sequence of integers will be represented as a string.</p>

<p>&nbsp;</p>

<p><b>Example 1:</b></p>

<pre>
<b>Input:</b> 1
<b>Output:</b> &quot;1&quot;
</pre>

<p><b>Example 2:</b></p>

<pre>
<b>Input:</b> 4
<b>Output:</b> &quot;1211&quot;</pre>

### Related Topics
  [[String](https://github.com/openset/leetcode/tree/master/tag/string/README.md)]

### Similar Questions
  1. [Encode and Decode Strings](https://github.com/openset/leetcode/tree/master/problems/encode-and-decode-strings) (Medium)
  1. [String Compression](https://github.com/openset/leetcode/tree/master/problems/string-compression) (Easy)

### Hints
<details>
<summary>Hint 1</summary>
The following are the terms from n=1 to n=10 of the count-and-say sequence:
<pre>
 1.     1
 2.     11
 3.     21
 4.     1211
 5.     111221 
 6.     312211
 7.     13112221
 8.     1113213211
 9.     31131211131221
10.     13211311123113112211
</pre>
</details>

<details>
<summary>Hint 2</summary>
To generate the <i>n</i><sup>th</sup> term, just <i>count and say</i> the <i>n</i>-1<sup>th</sup> term.
</details>
